# RUNA - Harbor Rescue (phone test build)

A web build of RUNA's first dungeon, Harbor Rescue: pick a class and play it with four AI party members.
It's a test build for playing on a phone in the browser (Safari on iPhone).

**Play:** https://jbowling31.github.io/runa-web/

- First load downloads about 480 MB, so use Wi-Fi. After that, the browser usually keeps it.
- The game file (`index.pck`, 430 MB) is over GitHub's 100 MB file limit, so it's stored in `pck_parts/` and the
  Pages workflow joins it back together when it publishes.
- Built with Godot 4.7.2 (web, no threads; Terrain3D web library included).
