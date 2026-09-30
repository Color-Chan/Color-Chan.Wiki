---
title: Sorting Colors
icon: lucide/arrow-down-up
description: Guide on how to automatically sort your Color-Chan color list
---

??? success "Requirements"

    This section assumes that you have already added colors to your server. If you haven't done so yet, please refer to the [Adding Colors](./adding-colors.md) section first.

Color-Chan can automatically sort your color list for you, so you don't have to manually [reorder the color roles](./color-order.md) one by one. You choose how you'd like the colors sorted, preview
the result, and only apply it once you're happy with how it looks.

## Previewing a sort

Use the `/sort color list type:<type>` command to generate a preview of your color list sorted the way you choose. This preview does not change anything in your server until you apply it.

The `type` option accepts the following sorting methods:

| Type                             | Description                                                                                                                                                               |
|----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Hue (Rainbow)                    | Sorts colors along the rainbow, from red through to violet.                                                                                                               |
| Luminance (Dark to Light)        | Sorts colors from the darkest to the lightest.                                                                                                                            |
| Hue & Luminance (Rainbow Shade)  | Sorts by hue first, then arranges each row from dark to light in a snake pattern, alternating direction row by row so the colors flow neatly through the color list grid. |
| Saturation (Dull to Vivid)       | Sorts colors from the dullest (greyest) to the most vivid.                                                                                                                |
| Name (A to Z)                    | Sorts colors alphabetically by their name.                                                                                                                                |
| Creation date (Oldest to Newest) | Sorts colors by the order they were added to the color list.                                                                                                              |

Once generated, the preview shows an **Apply Sorting** button.

!!! info "Note"

    Generating a preview can take a moment for larger color lists, Color-Chan will show a loading message while it puts the images together.

## Applying a sort

Press **Apply Sorting** on the preview to reorder the color roles in your server to match it. This updates the position of every color role and saves the new order to your color list, the same as if
you had reordered the roles manually.

??? info "Permissions"

    Applying a sort is more restrictive than most other color commands. You need to be the server owner, have the `Administrator` permission, or have a [color management role](../permissions/color-managers.md) — having the `Manage Roles` permission by itself is not enough unless a color management role has been set up.

    Color-Chan also needs the `Manage Roles` permission, and its highest role must be above the color roles it's trying to reorder.

You can verify the new order afterwards with the `/color list` command.
