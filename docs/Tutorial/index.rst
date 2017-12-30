.. _Tutorial:

Tutorial
=========
This section presents tutorials on
 
1. Sliding window 
2. Batch window. 

The source and validation datasets that go into generating these scenarios are also available.

Sliding Window
^^^^^^^^^^^^^^^
In Sliding windows, incoming signals may not be very well characterized and temporal proximity can be exploited to enable opportunistic
loss-limited sampling by changing the size of the windows (within a suggested range) to better identify characteristic signal features. 

         
Dataset
-------
The dataset used to create and validate the sliding windows scenario can be downloaded below

:download:`Source1 <Dataset/source1.csv/>`
:download:`Source2 <Dataset/source2.csv/>`
:download:`Source3 <Dataset/source3.csv/>`
:download:`PartialFacts1 <Dataset/partialVerification1.csv/>`
:download:`PartialFacts2 <Dataset/partialVerification2.csv/>`
:download:`PartialFacts3 <Dataset/partialVerification3.csv/>`
:download:`Facts1 <Dataset/verification-activity1.csv/>`
:download:`Facts2 <Dataset/verification-activity2.csv/>`
:download:`Facts3 <Dataset/verification-activity3.csv/>`


Video
------
A video illustrating the the use of sliding windows is shown below
https://vimeo.com/175744365

Batch Window
^^^^^^^^^^^^^
In Batch window, signal are sampled by splitting them into batch window sizes. This helps improve runtime in scenarios where there is 
repetition of temporal patterns.

Dataset
-------
The dataset used to create and validate the batch windows scenario can be downloaded below

:download:`Source File <Dataset/source.csv/>`
:download:`Verification File <Dataset/verification-health.csv/>`

Video
------
A video illustrating the the use of batch windows is shown below
https://vimeo.com/225296153




     

