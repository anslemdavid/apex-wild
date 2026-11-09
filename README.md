<div align="center">

# APEX WILD

### Pick your ride. Claim the city. Own the finish.

**A standalone 3D arcade racer with custom cars, city-inspired circuits, and combat power-ups.**

[▶ Play Apex Wild](https://anslemdavid.github.io/apex-wild/)

</div>

---

Six racers. Three laps. One winner. Choose a car, line up on the grid, and race
through nine distinctive environments. Collect power-ups, outmaneuver AI
rivals, and chase the lead in your browser.

## The race

- **Six custom rides:** Emerald Lowrider, Night Interceptor, Camo GT, Retro
  Wedge, Mint Sparkle Coupe, and Papaya Carbon Hypercar.
- **Nine environments:** Miami Sunset, Miami Night, New York, Berlin, Tokyo,
  Shanghai, London, Swiss Alps, and Forest Day.
- **Combat racing:** use Nitro, Shock, Bolt, and Mine pickups to swing the race.
- **Race-day essentials:** AI opponents, three laps, minimap, touch controls,
  engine audio, pause, bumper camera, lap banners, and wrong-way warning.
- **Resolution options:** toggle 4K rendering; the game automatically falls
  back to performance-friendly rendering when needed.

## Controls

| Action | Keyboard |
| --- | --- |
| Accelerate / brake | `W` / `S` or `↑` / `↓` |
| Steer | `A` / `D` or `←` / `→` |
| Drift | `Shift` |
| Use item | `Space` or `E` |
| Pause / resume | `P` or `Esc` |
| Chase / bumper camera | `C` |
| Change environment | `T` |
| Toggle high-resolution mode | `Q` |
| Respawn | `R` |
| Mute | `M` |

Touch controls appear automatically on touch-screen devices.

## Play locally

The game is a static web page and has no build step or runtime dependencies to
install. Three.js is bundled locally, so the game engine itself does not need
an internet connection.

1. Download this repository or clone it:

   ```powershell
   git clone https://github.com/anslemdavid/apex-wild.git
   cd apex-wild
   ```

2. Open `index.html` in a recent browser. If local-file restrictions prevent
   WebGL from starting, serve the folder:

   ```powershell
   py -m http.server 8000
   ```

   Then visit <http://localhost:8000>.

## GitHub Pages

The included GitHub Actions workflow deploys the site automatically whenever
you push to `main`. In **Settings → Pages**, select **GitHub Actions** as the
deployment source. After the first successful workflow run, play online at
<https://anslemdavid.github.io/apex-wild/>.

## Credits and license

The game and its visual assets are included in `index.html`. Three.js r128 is
bundled as `three.min.js` under the MIT license; see
[`THREE-LICENSE.txt`](./THREE-LICENSE.txt).
