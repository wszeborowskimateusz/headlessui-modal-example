# Example app showcasing a problem described in https://github.com/tailwindlabs/headlessui/discussions/3648

## To run it open 2 terminals

- Terminal 1: npm i && npm run watch
- Terminal 2: cd example && npm i && npm run dev

Scenario:

1. Click on the Open button
2. Click on the Open button on the Modal
3. Click outside

## Current result:

- Both modals are being closed

## Expected result:

- Only the inner modal should be closed
