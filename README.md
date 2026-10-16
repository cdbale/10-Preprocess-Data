# 10-Preprocess-Data

Lecture 10 develops recipes, transformations, categorical encoding, and consistent preprocessing for the home-goods customer analysis from Lectures 06–09.

- Slide source: `10 Preprocess Data.Rmd` (ioslides).
- Student workbook: `10-starter-code.qmd`.
- Exercise 9 solution and existing five-point rubric: `Exercise 9 Solution.qmd`.
- Inputs: `home_goods_customers.csv` and `data_dictionary.pdf`; keep them beside the workbook.

The class uses `CampaignSpend ~ PreviousSpend + Treatment + Education` with seed 42 and an 80/20 split. Exercise 9 keeps CampaignSpend and Treatment but asks students to choose and justify additional pre-campaign predictors and preprocessing appropriate to their variables. It uses seed 42 and a 75/25 split, test MAE in dollars, full-data refitting after evaluation, and student-chosen customer profiles with prediction intervals. No particular transformations or number of model alternatives are required. The solution illustrates one acceptable approach.

The business question concerns the email-assignment effect and customer spending patterns. The lecture compares three models using test MAE in dollars, refits the selected specification on all customers, interprets its coefficients, and ranks 24 customer profiles with prediction intervals.

The starter preserves three earlier-topic practice gaps, adds a Your Turn workspace, and ends with the open live-coding activity. The slide assignment and separate solution/rubric use the revised model and paired profiles. The standalone `preprocessing-guide.pdf` matches the updated guide on source slide 9. Keep PDF documents in this lecture repository's root directory, as requested; do not place them in output subfolders.

`10-Preprocess-Data.html` and the identical `index.html` contain the current 46-slide presentation. The root `index.html` is the GitHub Pages entry point. Publication and Canvas verification are recorded in `Chat Completed`.
