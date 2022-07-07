## Amazon SageMaker Feature Store now allows adding new features to existing feature groups

[Amazon SageMaker Feature Store](https://aws.amazon.com/sagemaker/feature-store/) is a fully managed, purpose-built repository to store, update, search, and share machine learning (ML) features. The service provides feature management capabilities such as enabling easy feature reuse, low latency serving, time travel, and ensuring consistency between features used in training and inference workflows. A feature group is a logical grouping of ML features whose organization and structure is defined by a feature group schema. Until today, the features in a feature group were defined at the time of feature group creation, and the feature group schema was immutable.

Amazon SageMaker Feature Store is announcing the ability to evolve the feature group schema and add new features into existing feature groups after it was created. Now you can leverage the same feature group over time as models evolve to use new features, without the burden of creating and managing new feature groups. You can add one or multiple features to an existing feature group using the UpdateFeatureGroup API. You simply specify the name of the feature group to update and the name and type of each feature to be added.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5m15zsqp4eb1szj9b681.png)](https://k21technologies.samcart.com/referral/gBBzLUFj/wZNqvQpM5mBn2g53)

To learn more, please view the documentation [here](https://docs.aws.amazon.com/sagemaker/latest/dg/feature-store-update-feature-group.html). To get started, log into the [Amazon SageMaker console](https://console.aws.amazon.com/sagemaker/home).

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/amazon-sagemaker-feature-store-new-features-existing-feature-groups/