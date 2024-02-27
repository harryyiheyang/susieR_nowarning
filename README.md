# susieR_nowarning
This R package is a modified clone of the original susieR R package, available at https://github.com/stephenslab/susieR. It specifically removes the warning message "WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2". The primary reason for this modification is to enhance the user experience in projects where susieR is applied iteratively, as this warning can be repeatedly displayed under such circumstances, potentially cluttering the output and distracting the users. In particular, such warning information will still be shown even though XtX is symmetric, as discussed in https://github.com/stephenslab/susieR/issues/152.

The decision to remove this warning stems from observations in various projects that apply susieR in an iterative manner. In these scenarios, the repeated appearance of the warning message does not contribute to the analysis but rather, it may interfere with the user's ability to quickly assess the output of their computations. By eliminating this warning, the package aims to provide a cleaner interface, allowing users to focus on the essential results of their analysis without unnecessary interruptions.

An example is shown below:

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2

WARNING: XtX is not symmetric; forcing XtX to be symmetric by replacing XtX with (XtX + t(XtX))/2


