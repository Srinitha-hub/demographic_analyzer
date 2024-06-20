# demographic_analyzer

Explanation of Calculations:

1. Race Count: Uses `value_counts()` to count occurrences of each race in the `race` column.
2. Average Age of Men: Filters for males (`'sex' == 'Male'`) and calculates the mean age.
3. Percentage with Bachelor's Degree: Calculates the mean of a boolean mask where `True` indicates individuals with `'Bachelors'` education.
4. Percentage of High Earners with Advanced Education: Filters for individuals with `'Bachelors'`, `'Masters'`, or `'Doctorate'` degrees and computes the percentage who earn `>50K`.
5. Percentage of High Earners without Advanced Education: Computes the percentage of individuals without advanced degrees who earn `>50K`.
6. Minimum Work Hours: Uses `min()` to find the minimum value in the `'hours-per-week'` column.
7. Percentage of High Earners among Minimum Workers: Filters for individuals working the minimum hours and computes the percentage who earn `>50K`.
8. Country with Highest Percentage of High Earners: Calculates percentages of high earners by country and identifies the country with the highest percentage.
9. Top Occupation among High Earners in India: Filters for high earners in India (`'native-country' == 'India'`) and identifies the most common occupation.

Ensure your `adult.data.csv` file is correctly formatted and located in the same directory as your script. Adjust paths and column names

Dataset Source
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science.

