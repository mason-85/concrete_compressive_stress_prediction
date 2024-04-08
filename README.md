The compressive strength of concrete, a critical material in civil engineering, refers to its ability to withstand failure, particularly in the form of cracks. The 28-day compressive strength is a widely used metric for evaluating the performance of concrete in engineering applications, such as supporting structural loads. Accurately predicting concrete strength is crucial in construction projects to prevent potential catastrophic failures in civil infrastructures. Conversely, concrete with excessively high strength may lead to increased material costs and environmental concerns, such as elevated CO2 emissions.

Recent advancements in machine learning (ML) techniques provide an alternative solution to address the prediction problem. ML can effectively capture the intricate and non-linear relationship between concrete mixture proportions and strength. However, the utilization of large datasets is essential for training such models. In this context, the "concrete.csv" dataset is provided for this purpose. It's important to note that realistic industrial concrete strength data is limited, posing a challenge commonly known as the small dataset problem.

Below is a description of the attributes included in the dataset (concrete.csv):

- Cement: measured in kilograms per cubic meter of mixture
- Blast: measured in kilograms per cubic meter of mixture
- Fly ash: measured in kilograms per cubic meter of mixture
- Water: measured in kilograms per cubic meter of mixture
- Superplasticizer: measured in kilograms per cubic meter of mixture
- Coarse Aggregate: measured in kilograms per cubic meter of mixture
- Fine Aggregate: measured in kilograms per cubic meter of mixture
- Age: measured in days (1~365)
- Strength: concrete compressive strength measured in MPa (Target)</br></br>
The detailed explanations are availeable in the "concrete_compressive_stress_prediction.ipynb" file.
