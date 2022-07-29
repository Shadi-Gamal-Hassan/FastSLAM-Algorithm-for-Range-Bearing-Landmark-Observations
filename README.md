# FastSLAM-Algorithm-for-Range-Bearing-Landmark-Observations
FastSLAM is a Rao-Blackwellized particle filter for simultaneous localization and mapping.
The pose of the robot in the environment is represented by a particle filter. Furthermore,
each particle carries a map of the environment, which it uses for localization. In the
case of landmark-based FastSLAM, the map is represented by a Kalman Filter, estimating
the mean position and covariance of landmarks and we implement the landmark-based FastSLAM algorithm assuming
known feature correspondences.
