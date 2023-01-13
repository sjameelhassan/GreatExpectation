# GreatExpectation

What is GX?

Great Expectations is a leading open-source tool for validating, documenting, and profiling data. The design pattern under the surface is very well known to developers — automate unit tests. Some developers hate unit tests and are reluctant to do them until they are well-integrated with CI/CD pipelines. Great Expectation can be well-integrated with the data analytics platform, such as Databricks, AWS EMR, Airflow, BigQuery, etc.

Key Features

Expectations

Expectations are assertions about your data. In Great Expectations, those assertions are expressed in a declarative language in the form of simple, human-readable Python methods.

Automated data profiling

Writing pipeline tests from scratch can be tedious and overwhelming. Great Expectations jump starts the process by providing automated data profiling. The library profiles your data to get basic statistics, and automatically generates a suite of Expectations based on what is observed in the data.

Data validation
Once you’ve created your Expectations, Great Expectations can load any batch or several batches of data to validate with your suite of Expectations. Great Expectations tells you whether each Expectation in an Expectation Suite passes or fails, and returns any unexpected values that failed a test, which can significantly speed up debugging data issues!

Data Docs
Great Expectations renders Expectations to clean, human-readable documentation, which we call Data Docs, see the screenshot below. These HTML docs contain both your Expectation Suites as well as your data Validation Results each time validation is run – think of it as a continuously updated data quality report.
