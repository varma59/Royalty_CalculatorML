# Royalty_CalculatorML
Analyzing Movie Royalties: Cloud-Enhanced Insights through Machine Learning Models
To calculate the royalty for a movie based on the IMDb dataset as of 2024, the script utilizes Python libraries such as pandas, numpy, and matplotlib. The dataset, assumed to be stored in a variable named 'cleaned_data', contains IMDb details including runtime, average rating, and number of votes. The script prompts the user to input the movie's runtime, average rating, and number of votes. Then, it calculates above-average thresholds for runtime and number of votes using quantiles from the dataset.

The royalty calculation prioritizes IMDb rating, runtime, and number of votes, where a movie is considered "good" if it meets certain criteria: IMDb rating greater than or equal to 8, runtime longer than the runtime threshold, and number of votes exceeding the likes threshold. If these conditions are met, a royalty percentage of 5% is applied. Finally, the royalty amount is displayed as a percentage.

The script demonstrates the use of pandas for data manipulation, numpy for numerical computations, and matplotlib for visualizations. Additionally, it imports gzip and shutil for handling compressed data and mpl_toolkits.mplot3d for 3D plotting capabilities.

A GitHub repository containing this script and any associated files would allow users to easily access and utilize it for calculating royalties based on IMDb data. Proper documentation and a README file would provide instructions on usage and dependencies. Additionally, users could contribute to the repository by suggesting improvements, adding new features, or fixing bugs.
