# XP calculation

## Base XP
> **Sensible default:** 10

This is the amount of XP a user is rewarded when writing a message.
This number should not be to low in order to give your users a feeling of progress.

## Length multiplier

In order to give users a bonus when writing longer messages you can add a length
multiplier.
In order to enable this fature specify the number of words required
to reach the bonus and then a precentage of the `Base XP` to award.

> For example: If you set the length multiplier to `10 words` and `10%` and the
`Base XP of 10`, a user will get `1` extra point for every `10 words.`

In the example above a 10 words message will give the user 11 points, and a 20 words message will give
the user 12 points.

## Flat XP bonuses

In addition to the lenght multiplier you can also add flat XP bonuses that will
be awarded after any number of words.

!> Only the last bonus will be applied. They do not stack.
