# Blink

*A QuarterbitGames original.*

You're a firefly caught in a web stretched across a barn doorway at night.
It's pitch black, and your glow is the only light you have. The spiders are already watching. All you've got is a flower.

**Bonk them off the web. Keep your glow alive. Survive the big one.**

## How to play

- **Your glow is your light.** You can only see what's near you, near the lantern, or in the moonlight. Spiders show up first as **glowing red eyes** in the dark.
- Your glow slowly fades. Grab the **glow drops** on the web to refill it.
- **Flower bonk:** swing your flower to knock spiders back. Knock them **off the edge of the web** and they fall for points. Each swing costs a petal, and petals grow back over time. With no petals left you only get a weak stem bonk.
- **Flash:** spend 30 glow to light up the whole web, stun nearby spiders and scare them away.
- Collect every glow drop to summon **the BIG one**. It stalks you, crouches before it lunges, and spawns babies. Flash it to stun it, and stunned bonks do **double damage**.
- **Every night the web gets smaller.** There's less room and more spiders.

### Spiders
| Spider | What it does |
|---|---|
| Crawler | Wobbles straight at you |
| Jumper (purple mark, from night 3) | Crouches with its eyes flaring, then leaps |
| The BIG one | 8 eyes, a health bar, lunges, spawns babies |

## Controls

| Action | Gamepad | Keyboard |
|---|---|---|
| Fly | Left stick / D-pad | WASD / Arrows |
| Aim bonk (optional) | Right stick | (aims where you move) |
| Flower bonk | A · X · RB · RT | Space · J |
| Flash | B · Y · LB · LT | Shift · K · E |
| Pause | Start | Esc · P |
| Music on/off | Select / Back | M |
| Menus | Stick / D-pad + A | Arrows + Enter |

You'll get rumble if your controller supports it.

## Music

Drop a track at **`audio/theme.mp3`** and it loops automatically. Browsers only allow audio after you interact, so it starts on your first key press or click. It gets quieter when you pause or lose, and your mute setting is remembered. With no file there, the game runs fine with just its sound effects and crickets.

## Run it

It's one file, `index.html`. Open it in a browser, or serve the folder with `python3 -m http.server 8000` and go to http://localhost:8000. No build step and no dependencies (it uses Google Fonts if they're reachable).

### Play it online with GitHub Pages
```bash
gh api -X POST repos/Etsimulocto/Blink/pages -f "source[branch]=main" -f "source[path]=/"
```
The game will then be at **https://etsimulocto.github.io/Blink/**
