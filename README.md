# SPD-Kohaku

A fan-made mod of [Shattered Pixel Dungeon](https://shatteredpixel.com/shatteredpd/) featuring **Kohaku** as the only playable hero.

> **Website**: [tonn5698-glitch.github.io/SPD-Kohaku-Web](https://tonn5698-glitch.github.io/SPD-Kohaku-Web/)

## About

SPD-Kohaku replaces the standard Duelist class with **Kohaku**, a custom character with a complete 4-direction sprite system and RPG Maker-style dialog portraits. The mod locks all other hero classes, making Kohaku the sole playable character.

### Features

- **4-Direction Sprite System** &mdash; Real RPG Maker-style facing (DOWN/LEFT/RIGHT/UP), replacing the base game's horizontal flip
- **Custom Animations** &mdash; Drink, eat, hurt, dizzy, and transformation animations
- **Monini Transform** &mdash; Kohaku transforms into "Monini" form when under speed buffs
- **RPG Dialog System** &mdash; Visual-novel style dialog with face portraits and typewriter text
- **Configurable Speed** &mdash; Adjustable movement speed from slow to fast

## Characters

| Character | Creator | Status |
|-----------|---------|--------|
| Kohaku | BAYACHAO | Used with permission |
| Warrior, Mage, Rogue, Huntress, Cleric | Evan Debenham (SPD) | Locked / Not playable |

## Building

```bash
export JAVA_HOME=/usr/lib/jvm/java-17-openjdk-arm64
export ANDROID_HOME=/opt/android-sdk
sh ./gradlew :android:assembleDebug --no-daemon
```

**Requirements:**
- JDK 17
- Android SDK

Output: `android/build/outputs/apk/debug/android-debug.apk`

## License

This project is licensed under **GPLv3**, consistent with the upstream Shattered Pixel Dungeon license.

See [copyright.html](copyright.html) for full attribution and licensing details.

## Credits

- **Shattered Pixel Dungeon** by [Evan Debenham](https://github.com/00-Evan/shattered-pixel-dungeon) &mdash; GPL-3.0
- **Pixel Dungeon** by [Watabou](https://watabou.itch.io/) &mdash; GPL-3.0
- **Kohaku** character by [BAYACHAO](https://www.deviantart.com/bayachao) &mdash; Used with permission
- **libGDX** &mdash; Apache 2.0

## Contact

For copyright concerns or questions: [GitHub Issues](https://github.com/tonn5698-glitch/SPD-Kohaku-Web/issues)
