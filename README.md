# Alpha Large Volume Trade Indicator

Sierra Chart ACSIL custom study: large volume trade bubbles with aggregation, multi-day historical rebuild, and Large Print Net Delta line.

## Download

[⬇ Download Latest Release (v1.4)](https://github.com/TraderAlpha-1/Alpha-Large-Volume-Trade-Indicator/releases/latest/download/AlphaLargeVolumeTradeIndicator_64.dll)

## Compatibility

Requires **Sierra Chart 2969 or newer** (64-bit, Windows). v1.4 will not load on older versions: update Sierra Chart first via Help > Download Current Version.

Sierra Chart finalized the ACSIL interface in version 2969, so this build should keep working on later releases.

## Installation

1. Download `AlphaLargeVolumeTradeIndicator_64.dll`
2. Close Sierra Chart. If you have an older copy, delete it from your Sierra Chart `Data` folder
3. Copy the new DLL to your Sierra Chart `Data` folder (e.g. `C:\SierraChart\Data`)
4. Reopen Sierra Chart. In Sierra Chart: Analysis → Studies → Add Custom Study → Alpha Large Volume Trade Indicator
5. Re-enter your settings. Bubbles rebuild from history, then appear live

For the two-panel delta line configuration and full setup guide, see the [Substack guide](https://traderalpha1.substack.com/p/alpha-large-volume-trade-indicator-1a4).

## Changelog

**v1.4**
- Recompiled against Sierra Chart 2969 headers (required after the 2969 interface update)
- Fixed: volume label color setting is now applied
- Fixed: Hide Study now hides the volume labels (un-hiding rebuilds from history, so keep "Rebuild Historical Trades on Load" = Yes)

**v1.3**: live trade fix for Sierra Chart 2911+

**v1.2**: initial public release

## License

Free to use. All rights reserved, source code not provided. See [LICENSE](LICENSE) for details.
