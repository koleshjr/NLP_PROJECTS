## Modeling Fake Climate Change Data
### Overview

Welcome to the "Modeling Fake Climate Change Data" project! In this project, we explore a dataset adopting the FEVER methodology, comprising 1535 real-world claims related to climate change collected from various sources on the internet. Each claim is meticulously paired with five manually annotated evidence sentences extracted from the English Wikipedia. These sentences either support, refute, or provide insufficient information to validate the corresponding claim, resulting in a total of 7675 claim-evidence pairs.
### Dataset Details
FEVER Methodology

The dataset follows the FEVER methodology, emphasizing the following key aspects:

    Real-world Claims: The dataset is grounded in real-world claims surrounding climate change, ensuring relevance and authenticity.
    Manually Annotated Evidence: Each claim is associated with five evidence sentences, manually annotated to support, refute, or lack sufficient information to validate the claim.
    Challenging Claims: The dataset includes challenging claims that encompass multiple facets of climate change issues.
    Disputed Cases: Some claims in the dataset involve both supporting and refuting evidence, adding complexity to the modeling task.

### Contents

    Dataset Information:
        Total Claims: 1535
        Total Evidence Sentences: 7675
        Annotation Labels: Support, Refute, Insufficient Information

    Dataset Structure:
        Each claim is accompanied by five evidence sentences.
        The evidence sentences are manually labeled with their corresponding annotation.

    Challenges and Considerations:
        Addressing complex claims that involve multiple facets of climate change.
        Handling disputed cases where both supporting and refuting evidence coexist.

### Usage

The dataset is valuable for training and evaluating models that aim to discern the veracity of climate change-related claims. It provides a diverse set of challenges, encouraging the development of robust models capable of navigating through nuanced and disputed cases.
### Technologies Used

    Programming Language: Python
    Libraries/Frameworks: Transformers