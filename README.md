# DataWeave: The synthetic_data_generator app

`DataWeave` is an innovative application designed to generate synthetic data using GPT-4, tailored for various domains and use cases. 

1. This is developed as a working prototype for a scalable version which in the future is capable of generating synthetic data at an enterprise scale.
2. We used ``

## Overview
### UI Generation Using Streamlit
•	The Streamlit Python code sets up the basic user interface for DataWeave.
•	Branding and Description: Includes a logo, central title, and a description about the app's purpose.
•	Session State Initialization: Initializes variables for storing field names and types.
•	Data Field Management: Users can specify data fields manually with various data types.
•	Custom CSS Styling: Enhances the UI with CSS for better visual appeal.
•	Manual Data Specification: Users can add fields, define names/types, select domains, and provide descriptions.
•	CSV File Upload: An option for users to upload a CSV file for data generation.
### Integration with GPT-4 for Synthetic Data Generation
•	The app aims to use GPT-4 to generate synthetic data based on user inputs.
•	Formulate Prompts: Converts user inputs into prompts for GPT-4.
•	Integration with GPT-4: Involves using the OpenAI API for generating data.
•	Data Processing: The generated data is processed and can be downloadable in 4 different formats.


## Salient Features:
1.	`Versatile Data Input Methods: Whether you prefer the hands-on approach of manually adding field names and types or the efficiency of uploading via CSV, DataWeave accommodates your style. Our platform is crafted for flexibility, ensuring a user-friendly experience that adapts to your workflow.
2.	`Customization` : With DataWeave, you're in control. Select from 15 diverse domains like Medicine, Finance, and Logistics, and describe your data needs. Our system intuitively crafts prompts based on your inputs, ensuring the output is perfectly aligned with your domain's nuances.
3.	State-of-the-Art Data Accuracy: At the heart of DataWeave lies a sophisticated backend, harnessing the power of OpenAI's API to transform your inputs into synthetic data with unparalleled precision. The result? Data that's not just synthetic, but syntactically and semantically in tune with your domain's reality.
4.	`Flexible Data Export Options:` Accessibility is key. That's why DataWeave allows you to download your data in multiple formats: CSV, JSON, Excel, and TXT. This flexibility ensures seamless integration with your existing systems and workflows, making DataWeave a versatile tool in your arsenal.
5.	`Extensive Format Support:` Catering to a wide array of data types, DataWeave supports 19 field formats, including Text, Enum, Email, Boolean, Latitude, and Zipcode etc. This diversity empowers you to mimic real-world data scenarios more accurately, enhancing the realism and applicability of your AI models.
6.	`Domain-Specific Data Generation:` DataWeave isn't just about quantity; it's about quality. With support for 15 domains, our app generates data that's not just synthetic but is intricately crafted to reflect the specificities of your chosen field. This domain-specific approach ensures that the synthetic data you generate is as close to real-world data as possible.
7.	`Statistically sound results:`  Our app presents reports of robust tests that ensure data generated is statistically sound and consistent.

## Statistical Tests that ensure data significance:
1.	`Descriptive Statistics`
•	For All Input Types: Calculate mean, median, mode, range, standard deviation, and variance for numerical fields; frequency counts for categorical fields.
2.	`Data Format Validation`
•	For All Input Types: Validate that the generated data adheres to the specified formats (e.g., email, numeric ranges).
3.	`Correlation Analysis`
•	For Dataset Uploads: Compare the correlation coefficients of the synthetic data with those of the uploaded dataset.
•	For Manual Entry and CSV Uploads: If multiple fields are expected to be correlated, calculate and report correlation coefficients.
4.	 `Distribution Checks`
•	For All Input Types: Where distribution information is provided or inferred, verify that the generated data matches these distributions.
5.	`Factor Analysis`
•	Primarily For Dataset Uploads: Perform if the dataset is large/complex enough for underlying factors. Compare factor loadings with those of the uploaded dataset.
6.	Distribution Comparisons
•	For Dataset Uploads: Use tests like the Kolmogorov-Smirnov test to compare the distributions of the synthetic data with the uploaded dataset.

