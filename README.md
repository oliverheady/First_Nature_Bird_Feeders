# First_Nature_Bird_Feeders
Used methods in the Pandas and Numpy libraries to scrub a dataset that could then eventually be used for modeling and analysis.

Each record in the dataset gives details about a visit to a hummingbird feeder by a specific bird. Several data points are recorded for each visit, including:

VisitID: A unique identifier for each visit.
BirdName: The full (first and last) name of the bird that made the visit (note that there are only a few families of birds in the area that have made the visits listed in the dataset). No two birds have the same name.
BirdType: The species of bird (each named belongs to only one species: Anna’s, Calliope, or Rufous).
BirdSize: A rough approximation of the bird’s size, either S(mall), M(edium), L(arge), or XL (extra-large).
Gender: The gender of the bird that made the visit
VisitDate: The date of the visit.
VisitSpan: The timespan of the visit, including both the visit start time and the visit end time. These times are taken out to the hundredth of a second level of granularity.
Location: Which hummingbird feeder location was visited (there are a limited number of feeder locations that were tracked).
Hoverfeed: Whether the visit constituted a “hoverfeed”, in which the bird hovered while feeding (rather than sitting on the perch provided).
Amount: The amount of (liquid) hummingbird food that was consumed by the bird on the visit.
