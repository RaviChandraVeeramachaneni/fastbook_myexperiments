<u><h3>Experiment-1 : chap_1_exp_1.ipynb</h3></u>

Note: The first two cells in the notebook are to check which GPU has been allocated by the google colab and the amount of RAM. And these are not part of the fastbook learning and not needed for learning FastAI Libary.

In this experiment, I tried learning about each class, every method in it and its parameters that are used as part of the first model like:
ImageDataLoaders.from_name_func(...)
ImageDataLoaders.from_path_func(...)

And, then I tried implementing the first model and learned how it performed. I have <strong>ran multiple epochs</strong> to see if I can get the error_rate of less than or equal to 0.02 as described in the book. <strong>And I acheived at 6th epoch (fine_tune(6))</strong>. I also learned that overdoing this is increasing the error_rate.

The detailed explanation of the above is written in the following blogpost's titled "Deep Learning for Coders / Chapter-1 / Week-1" & "Deep Learning for Coders / Chapter-1 / Week-2": https://ravichandraveeramachaneni.github.io/
