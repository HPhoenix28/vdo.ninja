---
description: Optional audio meter style type
---

# \&meterstyle

General Option! ([`&push`](../../source-settings/push.md), [`&room`](../../general-settings/room.md), [`&view`](../view-parameters/view.md), [`&scene`](../view-parameters/scene.md), [`&director`](../../viewers-settings/director.md))

## Aliases

* `&meter`

## Options

| Value                   | Description                                                                                                                 |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| `1` \| (no value given) | will show the VU-style meter that the director has by default already                                                       |
| `2`                     | will show a green-border around the guest's video when they are talking                                                     |
| `3`                     | will show a little green dot in the top-right corner when the guest's talking; this is default for the guest's view already |

## Details

If you add this to a director's/guest's URL, it will show an optional audio style type, when a guest is talking.

## Related

{% content-ref url="style.md" %}
[style.md](style.md)
{% endcontent-ref %}