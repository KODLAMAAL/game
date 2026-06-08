# The Seven Gates of Kyoto — Source Code

## File Structure
- src/App.jsx                              App router & auth wrapper
- src/index.css                            Design tokens, fonts, CSS animations
- tailwind.config.js                       Tailwind theme config
- src/lib/gateData.js                      All 6 gate puzzles & final code
- src/pages/Home.jsx                       Main page & landing view
- src/components/game/GateMap.jsx          Gate selection map
- src/components/game/GateChallenge.jsx    Puzzle challenge screen
- src/components/game/FinalGate.jsx        Final gate & victory screen
- src/components/ui/ToriiGate.jsx          Torii gate UI component
- src/components/effects/SakuraPetals.jsx  Falling sakura petal animation
- src/components/effects/FogEffect.jsx     Drifting fog layer
- src/components/effects/DragonBackground.jsx  Ink-wash landscape SVG
- src/components/effects/InkWashTexture.jsx    Paper/parchment texture

## Tech Stack
React + Vite + Tailwind CSS + shadcn/ui + framer-motion

## Dependencies (add to package.json)
- framer-motion
- lucide-react
- @tanstack/react-query
- react-router-dom
