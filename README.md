# low-power-timer
Timer aimed to be as efficient as possible on power consumption by using as little as possible to fullfil timer function.
The idea is by using the captured timestamp when timer started and the timestamp when pause / stop initiated. These two values then can be subtracted to gain relative time.
