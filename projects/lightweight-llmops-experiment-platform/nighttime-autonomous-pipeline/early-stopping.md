# Early Stopping

The pipeline stops when either condition is met:

1. MSE worsens for five consecutive iterations.
2. MSE reaches the target threshold.

These rules save compute, reduce over-optimization, and release capacity for later experiments. They also bound unattended overnight runs.
