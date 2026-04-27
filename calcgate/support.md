# CalcGate Support

Welcome to CalcGate support.

CalcGate is an app that helps you lock selected apps until you either solve a math challenge correctly or the preset unlock time is reached. It is designed to make unlocking more intentional by adding friction before access is restored.

## Main Features

- Lock selected apps or app categories
- Configure math difficulty
  - number of digits
  - math operations
  - number of questions
- Set a time-based unlock condition
- Unlock by either:
  - answering all math questions correctly
  - waiting until the preset unlock time is reached
- Reset challenge progress after a wrong answer
- Prevent settings changes while the lock is active

## How to Use

1. Open **Settings** in the app
2. Choose:
   - difficulty
   - operations
   - number of questions
   - restricted apps
3. Return to the home screen
4. Tap **Start Lock**
5. While the lock is active, selected apps remain restricted
6. To unlock, either:
   - tap **Solve to Unlock** and complete the math challenge successfully
   - wait until the preset unlock time is reached

## Important Notes

- FamilyControls permission is required for app restriction features
- You cannot change challenge settings or unlock settings while the lock is active
- If you answer a question incorrectly, your current challenge progress is reset
- The lock can be removed when all questions are answered correctly or when the preset unlock time is reached
- Current settings are stored locally on your device

## Troubleshooting

### The app asks for permission

CalcGate requires FamilyControls authorization to manage restricted apps. Please grant permission when prompted.

### I cannot change settings

If the lock is currently active, settings are intentionally disabled until the lock is removed. This prevents the difficulty, number of questions, restricted apps, or unlock time from being changed during an active lock.

### The lock does not start

Please make sure:

- FamilyControls permission has been granted
- at least one app or category has been selected
- the app is not already in a locked state
- the required lock settings have been configured

### I closed the app during a challenge

The app is designed to return to the home screen when reopened, rather than restoring an incomplete challenge screen. If the lock is still active, you can start the unlock challenge again or wait until the preset unlock time is reached.

### The unlock time has not been reached yet

If the preset unlock time has not been reached, selected apps will remain restricted unless you complete the math challenge successfully.
