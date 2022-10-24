# Measuring the One-Way Speed Of Light

![CC0 -- Creative Commons Zero license, No Rights Reserved](https://licensebuttons.net/p/zero/1.0/88x31.png)
![Public Domain Mark](https://licensebuttons.net/p/mark/1.0/88x31.png)

***No clocks needed!*** Just two *independent* timers.

Alright, timers *are* clocks, but what matters is that they do not need to be synchronized.

### First question/experiment: Is the speed of light the same in all directions?
- Prepare a dark tube with a laser at one end, and a photodetector at the other end.
- Configure a timer to fire a laser pulse after a specific repeating time interval (let's say every 5 seconds)
- Let the laser fire a few times; the photodetector will register these readings at the exact same interval (5 seconds in between each reading).
  - We don't yet know exactly how long the laser pulse is taking to reach the photodetector, but we know that it will remain constant under these conditions.
- Then, in between two pulses, rotate the tube into a different direction.
  - If light is faster in that direction, the next photodetector reading will happen slightly sooner than the expected interval (because faster light will reach the photodetector sooner).
  - If light is slower in that direction, the next photodetector reading will happen slightly later than the expected interval (because slower light will reach the photodetector later).
  - The difference between the expected interval and the measured interval is how much shorter or longer it took the laser pulse to reach the photodetector in that direction.
- This doesn't yet allow us to measure the one-way speed of light, but we could measure the absolute speed difference between the two directions:
  - Let's say the tube measures exactly 1 meter.
  - And let's imagine that after rotating the tube, the measured time interval is 5.000000001 seconds, instead of the expected 5 seconds interval.
  - This would mean that light traveling in that direction is slower by 0.000000001 m/s (relative to whatever it was in the previous direction).

### Let's make sure these results are accurate, by actually *measuring* the one-way speed of light:

- Let's continue under the exact same conditions as the initial experiment.
- Except this time, instead of rotating the tube, we will move the laser (with its timer) forward or backward (with extreme precision).
  - Another option would be to move the photodetector instead.
  - If the movement cannot be extremely precise, then the measure of the distance between the two points should be.
- This will give us two measurements with which to calculate the one-way speed of light (in that direction):
  - A distance measurement, which is how much we moved the laser/photodetector.
  - And a time measurement, which is the difference between the expected interval and the interval measured after moving the laser.
- For example:
  - In between two pulses, we move the laser back by 1 meter (it is now exactly 2 meters away from the photodetector).
  - The measured time interval for the next pulse is 5.00000000333564095198 seconds, instead of the previous 5 seconds interval.
  - This would mean that light traveling in that direction took 0.00000000333564095198 seconds (or 3.33564095198 nanoseconds) to travel 1 meter. As you can imagine, precision is of the essence (or a much larger scale experiment, to compensate for any missing precision).
  - Using the simple velocity formula (velocity = distance / time), we can calculate that the one-way speed of light in that direction is 299,792,458 m/s (1 meter / 0.00000000333564095198 seconds), which is what we expect it to be if c is constant in every direction.
  - Moving the laser back to its original position should register a symmetrical time interval of 4.99999999666435904802 seconds on the next pulse.
- It's basically the equivalent of measuring the speed of a baseball (or some other moving object):
  - The initial interval (5 seconds) gives us the first "picture"/reading (at point A).
  - Then, moving the laser give us the distance between two points (A & B).
  - Then, the difference between the initial interval (at point A) and the next interval (at point B) gives us the "second picture", which reveals the time it took for the laser pulse to travel over that distance.
  - Note that this measurement can only be taken once per change of condition! Afterwards, the interval will return to its expected value.

![CC0 -- Creative Commons Zero license, No Rights Reserved](https://licensebuttons.net/p/zero/1.0/88x31.png)
![Public Domain Mark](https://licensebuttons.net/p/mark/1.0/88x31.png)
