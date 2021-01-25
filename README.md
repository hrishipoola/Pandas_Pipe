# Pandas Pipe

I first came across pandas pipe last month at a Berlin Time Series Analysis meetup and in a TDS post. It's a great way to organize and streamline your code and automate multiple dataframe manipulations and visualizations, especially if you're working with many dataframes. I wish I had used it more before!

In a nutshell, pipe chains together operations, taking a dataframe-returning function or plot call and positional arguments as inputs. Let's demonstrate with a head-to-head comparison. Well first scrape Berlin district-level covid case data from Das Landesamt für Gesundheit und Soziales. We'll then perform several dataframe manipulations without and with pipe.

