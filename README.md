# Matchcress 1.0 TEST
Native Android one-match equation repair. Android8+ min26/target35. Package com.gg007.matchcress.

## Rules
Known one-match equation-repair adaptation with fixed plus and equals signs. Repair A+B=C by relocating exactly one existing digit segment into one empty digit slot. Standard seven-segment digits 0-9 only: 1 uses the two right bars, 6 includes the top, 9 includes the bottom, 7 has three bars. A match can move within one digit or between digits and may rotate. Tap a lit source, then a dim destination. Tap the selected source again to cancel, or another lit bar to change the source. Exactly one relocation is allowed per try; invalid shapes or a false sum require undo/reset. No operator changes, inequalities, extra digits or added/removed matches. Twelve original generated false starts, distinct repaired answers, each with exactly one valid source-destination repair. Undo/reset, levels and saved palette/segment letters.

## Download and status
https://mega.co.nz/#!4V1RwCZJ!p4q6H9ZTJzD4wbeNbqjTRwNNFaRuiPLC4rMmFKuXWwU
APK 16878 bytes; SHA256 73cc9c7210a88d00627abcf650c3dbbe0204bb674dbe770b0d2c755e9f611ffb. Original certificate SHA2561651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions; original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed-861110 generator enumerates every false one-digit addition and every occupied-source/empty-destination relocation, accepting only puzzles with one valid repair. Twelve distinct starts and repaired sums. Independent oracle decodes digit shapes from literal segment-letter strings and checks arithmetic by subtraction; it counts removed/added bars individually instead of production bit-counts and digit-mask lookup. Every 21-bit pattern per board is checked: 25,165,824 comparisons, plus 120,000 random/invalid masks, totaling 25,285,824. Exactly one repair per board. Source selection/cancel, empty-first, bounds, invalid-one-move and solved locks, undo/replay/reset pass. Actual drawing-adapter segment-center taps solve all twelve, plus and equals are inert, settings palette/segment letters persist, completion/levels/next/menus/privacy pass. Seven drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Every one of the 217 prior studio descriptions and 803 legacy descriptions was reviewed. Rejected Lights Out because legacy28 already flips lights. Make24 chooses operations over four numbers; Cagehaven/Crossfern enter digits into grid constraints; Stickcress partitions directional line cells. Matchcress instead conserves and relocates one physical digit segment across a false equation, requiring valid final digit shapes and arithmetic together. No matching factory mechanic found. Known matchstick-puzzle adaptation, not a globally new invention. Original generated equations, code and visuals, no source puzzles or images copied. Six fully read sources across solver/app publishers, printable activity guidance, a merchant and brainteaser editorial/reader corrections. Source disagreements about digit9 tails and operator changes are explicit: this edition uses standard masks and fixed plus/equals. Sources with freely movable signs are not this exact rule set.

## Build and tests
JDK17/AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/match-test src/com/gg007/matchcress/Board.java BoardTest.java then java -cp /tmp/match-test com.gg007.matchcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your private signing material. No signing secret is included. adapter/android contains the Java2D drawing adapter used with MatchAdapterTest.java, not an Android runtime.

## Privacy and branding
Matchcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, segment letters and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon, studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative218-card studio and publishing fragments privately preserved:
https://files.instinct.com/0t2mv5dc4ivz-matchcress-source-archive
https://github.com/iLanis-agent/matchcress holds README only, full Git source pending. Jekyll includes unchanged, no Pages settings changes or client loader. Both sites verified separately.

## Rule sources
https://www.manextapps.com/puzzles/matchstick-equation-solver/
https://partypagekit.com/one-stick-equation/
https://gregpuzzles.com/pages/matchstick-puzzle-solver
https://sticks.dv8.no/
https://playboardgames.org/how-to-play/matchstick
https://braineaser.com/brainteasers/7-matchstick-equation-puzzles/
