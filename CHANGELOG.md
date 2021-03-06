# Change Log

## [v1.0.1](https://github.com/semuxproject/semux/tree/v1.0.1) (2018-03-06)
[Full Changelog](https://github.com/semuxproject/semux/compare/v1.0.0...v1.0.1)

**Fixed bugs:**

- A validator node might stuck in sync process
    - Consensus: Don't sync when a validator is in FINALIZE state [\#655](https://github.com/semuxproject/semux/pull/655) ([semuxdev](https://github.com/semuxdev))
    - Consensus: Fix unconditional wait of SemuxSync\#isRunning [\#626](https://github.com/semuxproject/semux/pull/626) ([cryptokat](https://github.com/cryptokat))   
- API: Fix typos in API docs [\#666](https://github.com/semuxproject/semux/pull/666) ([orogvany](https://github.com/orogvany))
- GUI: Dispose address book dialog when the wallet GUI is locked [\#599](https://github.com/semuxproject/semux/pull/599) ([phash](https://github.com/phash))
- GUI: Import wallet imports addressbook too [\#576](https://github.com/semuxproject/semux/pull/576) ([orogvany](https://github.com/orogvany))
- GUI: Focus text field on right click [\#540](https://github.com/semuxproject/semux/pull/540) ([cryptokat](https://github.com/cryptokat))
- Net: Properly separate mainnet and testnet [\#568](https://github.com/semuxproject/semux/pull/568) ([cryptokat](https://github.com/cryptokat))
- CLI: Flush async loggers in `Launcher` class [\#539](https://github.com/semuxproject/semux/pull/539) ([cryptokat](https://github.com/cryptokat))

**Implemented enhancements:**

- Add Java 9 Support  [\#640](https://github.com/semuxproject/semux/pull/640) ([semuxdev](https://github.com/semuxdev))
- GUI: Support customized based unit and show full digits by default [\#681](https://github.com/semuxproject/semux/pull/681) ([cryptokat](https://github.com/cryptokat))
- GUI: Validate address alias length [\#660](https://github.com/semuxproject/semux/pull/660) ([orogvany](https://github.com/orogvany))
- GUI: Clean up address label [\#630](https://github.com/semuxproject/semux/pull/630) ([semuxdev](https://github.com/semuxdev))
- GUI: Update to new logo [\#606](https://github.com/semuxproject/semux/pull/606) ([orogvany](https://github.com/orogvany))
- GUI: Render to highest precision [\#602](https://github.com/semuxproject/semux/pull/602) ([orogvany](https://github.com/orogvany))
- GUI: Add Mnemonic Keys to the UI [\#589](https://github.com/semuxproject/semux/pull/589) ([phash](https://github.com/phash))
- GUI: Added feedback for empty names on address book entries [\#575](https://github.com/semuxproject/semux/pull/575) ([phash](https://github.com/phash))
- GUI: Add address book edit dialog [\#574](https://github.com/semuxproject/semux/pull/574) ([phash](https://github.com/phash))
- GUI: Add InputDialog to Windows TaskBar [\#571](https://github.com/semuxproject/semux/pull/571) ([phash](https://github.com/phash))
- GUI: Provide detailed tooltip for Data input [\#570](https://github.com/semuxproject/semux/pull/570) ([phash](https://github.com/phash))
- GUI: Add prefix to address in generated QR Code [\#566](https://github.com/semuxproject/semux/pull/566) ([phash](https://github.com/phash))
- GUI: Add a Title to Rename Account Dialog [\#563](https://github.com/semuxproject/semux/pull/563) ([orogvany](https://github.com/orogvany))
- GUI: Add a Title to Import Dialog [\#562](https://github.com/semuxproject/semux/pull/562) ([orogvany](https://github.com/orogvany))
- GUI: Add Semux Logo to About Dialog [\#560](https://github.com/semuxproject/semux/pull/560) ([orogvany](https://github.com/orogvany))
- GUI: Add command console [\#472](https://github.com/semuxproject/semux/pull/472) ([orogvany](https://github.com/orogvany))
- Consensus: Optimize transaction validation [\#675](https://github.com/semuxproject/semux/pull/675) ([orogvany](https://github.com/orogvany))
- Config: Disallow default API username or password [\#689](https://github.com/semuxproject/semux/pull/689) ([cryptokat](https://github.com/cryptokat))
- Net: Shuffle the list of nodes returned from GET\_NODES message in order to balance the load on nodes [\#679](https://github.com/semuxproject/semux/pull/679) ([cryptokat](https://github.com/cryptokat))
- Net: Add mainnet.semux.net as an alternative dns seed [\#662](https://github.com/semuxproject/semux/pull/662) ([cryptokat](https://github.com/cryptokat))
- Net, Config: Allow for additional DNS seeds [\#653](https://github.com/semuxproject/semux/pull/653) ([orogvany](https://github.com/orogvany))
- Core: Upgrade Leveldb From 1.8 to 1.18 [\#673](https://github.com/semuxproject/semux/pull/673) ([cryptokat](https://github.com/cryptokat))
- Core: Improve error reporting of UNVOTE transaction [\#623](https://github.com/semuxproject/semux/pull/623) ([cryptokat](https://github.com/cryptokat))
- Core: Optimize wallet lookup [\#601](https://github.com/semuxproject/semux/pull/601) ([orogvany](https://github.com/orogvany))
- API: Update error messages to be consistent [\#657](https://github.com/semuxproject/semux/pull/657) ([orogvany](https://github.com/orogvany))
- API: Validate `hash` on `getBlock` calls [\#654](https://github.com/semuxproject/semux/pull/654) ([orogvany](https://github.com/orogvany))
- API: Add a parameter 'name' to `/create_account` [\#614](https://github.com/semuxproject/semux/pull/614) ([cryptokat](https://github.com/cryptokat))
- API: Add parameter descriptions [\#600](https://github.com/semuxproject/semux/pull/600) ([orogvany](https://github.com/orogvany))
- API: Consistent error handling [\#556](https://github.com/semuxproject/semux/pull/556) ([orogvany](https://github.com/orogvany))
- API: Pretty print API response when get parameter pretty=true [\#555](https://github.com/semuxproject/semux/pull/555) ([orogvany](https://github.com/orogvany))
- API: Add sign/verify messages calls [\#549](https://github.com/semuxproject/semux/pull/549) ([orogvany](https://github.com/orogvany))
- API: Add a data field `transactionCount` to the response of `/get_account` API [\#543](https://github.com/semuxproject/semux/pull/543) ([cryptokat](https://github.com/cryptokat))
- API: Add data field TransactionType\#blockNumber [\#526](https://github.com/semuxproject/semux/pull/526) ([cryptokat](https://github.com/cryptokat))
- Tools: Upgrade Jackson to 2.9.4 [\#605](https://github.com/semuxproject/semux/pull/605) ([cryptokat](https://github.com/cryptokat))
- Windows: Detect Installation of Microsoft Visual C++ Redistributable Package Under Windows Platform [\#531](https://github.com/semuxproject/semux/pull/531) ([cryptokat](https://github.com/cryptokat))