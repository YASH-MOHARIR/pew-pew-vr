# PEW PEW!

A hands-only WebXR shooter for Meta Quest. Make a finger gun, raise your
thumb, and drop it to fire. Block bolts with an open palm, lean out of their
way, swipe an open hand to slash, and punch through glass walls with a fist,
on an endless climb through the sky, sector after sector, each ending in a
guardian fight.

**Play:** open **https://yash-moharir.github.io/pew-pew-vr/** in the Meta
Quest Browser, press **Enter XR**, put your controllers down, and show your
hands. Hand tracking must be on in the Quest's settings (Movement tracking).
Play seated; a run lasts a few minutes. First time? Shoot
**TUTORIAL** in the lobby.

| Move | How |
|---|---|
| Finger gun | index finger out (one or two fingers), other fingers curled, thumb up |
| Fire | drop your thumb, quickly |
| Reload | point the gun down |
| Block | open palm facing the bolt |
| Dodge | lean your head out of the bolt's path |
| Slash | swing an open hand fast (it cuts the blue-shielded robots) |
| Punch | make a fist and punch the glass walls as they reach you |
| Menus | shoot a button, or point an open hand and pinch |

This repository holds only the built game, published with GitHub Pages.
Entered in the Meta VR Start Developer Competition 2026 (Gaming track, New
Experience).

## Credits and licenses

Everything else in the game (code, models, music, and sound) is original.

- Demo hand model: the generic hand from the
  [WebXR Input Profiles](https://github.com/immersive-web/webxr-input-profiles)
  project, W3C Software and Document License
  ([licenses/webxr-input-profiles-generic-hand-W3C.txt](licenses/webxr-input-profiles-generic-hand-W3C.txt)).
- Demo hand poses: derived from [IWER](https://github.com/meta-quest/immersive-web-emulation-runtime)'s
  captured hand poses, MIT ([licenses/IWER-MIT.txt](licenses/IWER-MIT.txt)).
- Blaster A from Kenney's Blaster Kit, CC0
  ([licenses/kenney-blaster-kit-CC0.txt](licenses/kenney-blaster-kit-CC0.txt)).
- Scifi Pistol by Quaternius, CC0
  ([licenses/quaternius-scifi-pistol-CC0.txt](licenses/quaternius-scifi-pistol-CC0.txt)).
- Built with Meta's [Immersive Web SDK](https://iwsdk.dev) and
  [three.js](https://threejs.org) (both MIT).
