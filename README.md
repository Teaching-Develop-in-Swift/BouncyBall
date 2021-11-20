# BouncyBall
This is BouncyBall, from Develop in Swift Explorations Unit 3, completed into Part 3, where the onTapped function gets a little squirrelly. Use this version when you add a function to be called when the funnel is tapped and taps aren't registered in the simulator.

If you're following along in [the book](http://apple.co/developinswiftexplorations) and you tap on the funnel but your `dropBall` function isn't being called, try using this repository.

**Or**, if you're feeling brave,  [go to line 265 of Shape.swift](https://github.com/Teaching-Develop-in-Swift/BouncyBall/blob/33ec16d00e20bcd5b3cc6e5d3aa7321e1cf77e4a/Common/Shape.swift#L265), and change the `withTimeInterval:` parameter value from `0.1` to `0.2`.

This might feel like magic, but sometimes in the simulator the operation takes too long and the tap is cancelled before our code hears about it.
