# Update-a-feature-in-Realtime

This example shows how to change an existing feature on a map by updating its data.

It shows the progression of a path by adding new coordinates to a feature in a line layer. This approach is useful for visualizing real-time data sources.

Calling setData begins a new render cycle which makes the updates appear in real time without explicitly creating an animation. panTo then follows the leading edge of the line to keep it on screen.


![image](https://user-images.githubusercontent.com/118595650/202859440-9e5cb4e9-f128-48ed-91c2-d6e5ba9e5165.png)
