# Custom Game Cleaner
It cleans addon sounds, models and materials folders

## Usage
Put it (cleaner.js) into `dota 2 beta\game\dota_addons\your_addon\` and run with.
```batch
node cleaner
```
P.S.: it cleans as much as it can, so it's not needed to run this a few times without modifying anything

P.P.S.: it MAY clean something that you may need - for example, if you're overriding default DotA 2 files - this happens because it's searching for file usage within addon folders

Also, it's recommended to remove this file after cleaning, otherwise next re-upload of addon will include it in VPK

## Dependencies
Pure latest NodeJS (you can download it from https://nodejs.org)
