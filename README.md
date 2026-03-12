# crossover-reset

A script that resets the CrossOver trial period on macOS, allowing you to continue using it beyond the 14-day window.

It does three things:

1. Closes CrossOver if it's running
2. Resets the trial start date in CrossOver's preferences
3. Removes the expiration block on all installed bottles

## Usage

Run this one-liner in your terminal:

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/hexxt-git/crossover-reset/main/crossover_reset.sh)
```

Then reopen CrossOver.
