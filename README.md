# Chat KPI Calculator

A one-page calculator for chat performance. You type in 4 numbers from your chat report and it shows your key percentages right away. Nothing is saved or sent anywhere. It all runs in your browser.

## What you enter

- **Total chats**: every chat in the period.
- **Leads**: chats that turned into a lead.
- **AI-handled chats**: chats the AI handled.
- **Bogus chats**: spam, tests, or junk chats.

## What it calculates

| Result | Formula | In plain English |
|---|---|---|
| Valid chats | Total chats minus Bogus chats | The real chats, after the junk is removed. |
| Conversion % | Leads ÷ Valid chats | Out of the real chats, how many became leads. |
| AI share % | AI-handled chats ÷ Valid chats | Out of the real chats, how many the AI handled. |
| Bogus % | Bogus chats ÷ Total chats | Out of all chats, how many were junk. |

Conversion % and AI share % use valid chats, so junk chats don't drag them down. Bogus % uses total chats, because it measures how much of everything was junk.

## Example with 600 chats

Say last month you had 600 total chats, 60 bogus chats, 81 leads, and 405 AI-handled chats.

- **Valid chats**: 600 minus 60 = **540**
- **Conversion %**: 81 ÷ 540 = **15.0%**
- **AI share %**: 405 ÷ 540 = **75.0%**
- **Bogus %**: 60 ÷ 600 = **10.0%**

If a number it needs to divide by is 0, the result shows a dash (–) instead of an error.

## Input checks

The page shows a warning if the numbers don't add up: when Bogus chats are more than Total chats, or when Leads or AI-handled chats are more than Valid chats. Fix the inputs and the warning goes away.

## How to open it

1. Download `index.html` from this repo (click the file, then the download button).
2. Double-click the file. It opens in your web browser.
3. Type your numbers. The results update as you type.

No install, no internet connection, and no sign-in needed.
