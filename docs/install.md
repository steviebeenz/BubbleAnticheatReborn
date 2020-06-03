# Install Bubble Anticheat

1. First off, download [Skript](https://github.com/SkriptLang/Skript/releases)
2. Now install [SkUtilities](https://github.com/tim740/skUtilities/releases)
3. Restart your Server (don't reload)
4. Download the latest release of
   [Bubble Reborn](https://github.com/steviebeenz/BubbleAnticheatReborn/releases/tag/0.0.3)
   to plugins/Skript/scripts/getbubble.sk
5. Restart your server. Bubble will install itself and restart your server when
   its done.

## IMPORTANT: MineHut:

If you are on Minehut, first off, move to a proper hosting company. If this is
not possible, download this Minehut compatible release:
[Bubble Reborn for MineHut](https://github.com/steviebeenz/BubbleAnticheatReborn/releases/tag/0.0.2)

## Advanced Setup:

### The default perms (these are customizable in plugins/bubble/config.yml)

manage: "bubble.manage" Bypass: "bubble.bypass" CaptchaBypass:
"bubble.captcha.bypass" GUI: "bubble.gui" Notify: "bubble.notify"
PerformanceRun: "bubble.performance" Player: "bubble.player" ReportSend:
"bubble.report.send" ReportReceive: "bubble.staff.report.receive" Status:
"bubble.player.status" Theme: "bubble.theme"

## Setting up Autoban/Autokick:

1. Open plugins/bubble/config.yml.
2. Locate the "cheat" category
3. Enable your the automated actions you want.
4. If you use Autoban, customize it in the "ban" category.

## Enabling Captcha

1. Open plugins/bubble/config.yml.
2. Locate the "Bot Prevention" category
3. Change "Captcha" to true
4. Customize any other settings to your needs.
