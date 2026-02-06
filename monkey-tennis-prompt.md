Build me a browser-based web game called "Monkey Tennis" — a fun, playable tennis game where you control a monkey playing tennis against an AI opponent monkey.

## Theme & Tone

The game should be inspired by the comedic spirit of Alan Partridge — the concept of "Monkey Tennis" was famously his desperate, barrel-scraping TV pitch. Lean into that energy:

- The title screen should have a gloriously over-the-top presentation, as if this is the greatest TV show ever conceived — think dramatic tagline like "The Sport. The Primates. The Drama." or "From the mind of a genius..."
- Include brief, absurd Partridge-style commentary/quotes between points or games (e.g., "Back of the net!", "Jurassic Park!", "That was textbook!", "Smell my cheese, you mother!"). Make them appear as commentary text overlays. Invent original ones in a similar style too — short, punchy, absurdly confident non-sequiturs.
- The overall vibe should be: someone actually made this show and it's being presented with deadly seriousness despite being utterly ridiculous.
- Include a fake "Commissioned by BBC Norfolk" or similar joke in the footer/credits.

## Gameplay

- 2D side-view tennis court (think retro Pong-meets-tennis aesthetic but with monkey sprites/characters)
- Player controls one monkey on the left side, AI controls the other on the right
- Controls: Up/Down arrow keys (or W/S) to move the monkey, Spacebar to swing the racket
- Ball physics should feel satisfying — angles change based on where the ball hits the racket and timing of the swing
- Proper tennis scoring: 0, 15, 30, 40, Deuce, Advantage, Game. Play a full set to 6 games (with tiebreak at 6-6)
- The monkeys should have simple but charming animations (idle bounce, swing, celebrate, dejection)
- Ball speed should gradually increase as rallies get longer to build tension

## Visual Style

- Bright, fun colour palette — green court, blue sky background
- The monkeys should be cartoonish and expressive
- Use CSS/canvas animations — no external sprite sheets needed
- Scoreboard displayed prominently, styled like a TV broadcast overlay (think Sky Sports but cheaper — more like a local access channel)
- Add subtle screen effects like a slight CRT/VHS filter or scanlines to sell the "dodgy TV show" aesthetic

## Technical Requirements

- Single HTML file with embedded CSS and JavaScript (or a small set of files if cleaner)
- Use HTML5 Canvas for the game rendering
- No external dependencies — everything self-contained
- Should work in modern browsers
- Include a start screen, gameplay, and a game-over/set-won screen
- Add simple sound effects using the Web Audio API (ball hit, point scored, crowd reaction)

## Bonus Features (if feasible)

- A "Partridge Commentary" toggle that shows running text commentary in his style
- Different difficulty levels named appropriately (e.g., "North Norfolk Digital", "BBC2 Friday Night", "Primetime ITV")
- A brief intro sequence/animation when the game loads — like a fake TV show opening
- Crowd cheering that gets more enthusiastic during longer rallies
- Banana power-ups that occasionally appear on court for a speed boost

Make it fun, polished, and funny. This is the game Alan Partridge always dreamed of. Let's make it real.
