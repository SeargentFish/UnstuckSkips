# UnstuckSkips

This is a fork of the original [UnstuckSkips addon](https://github.com/aaronma37/UnstuckSkips). It's maintained by SeargentFish.

## Acknowledgements
- aaronma37/yazpad: Original addon
- Zarant: Logout skip locations
- Tactics and TommySalami: Logout skips discoveries and research; consulting
- Semlar: Original library for drawing lines on map

## Notes
This addon is experimental; don't rely on the unstuck skip locations too much. To use this addon, open the map and click the `Show UnstuckSkips` button.  Red `x`'s are locations where the unstuck skips will teleport you to. The red lines are Voronoi partitions which act as boundaries between different unstuck skip teleport locations.  The idea is that if you perform a unstuck skip, you will be teleported to the location indicated by the `x` that is within the polygon that you are in.
