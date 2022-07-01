## Amazon FinSpace releases APIs to assign granular user permissions

With the release of new granular permission APIs, Amazon FinSpace customers can now fully manage user access within their FinSpace environment using the AWS SDK and CLI. This allows customers to integrate configuration of FinSpace access controls into their identity orchestration workflows to keep FinSpace in sync with their organization’s access policies.

For example, when a user joins an equity research team that uses FinSpace, they can be automatically enabled in FinSpace and setup to have access to the datasets used by for equities analytics. If this user later moves to the fixed income analysis team, their access to the original datasets can be removed and they can be given access to the datasets used by the fixed income team. Finally, if this user leaves the customer’s organization, their access can be automatically deactivated in FinSpace.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r71m2wk06x3ib803b96l.png)](https://serverspace.io/ref/466650)

[Amazon FinSpace](https://aws.amazon.com/finspace/) is a fully managed analytics service for financial services customers that enables analysts to access and analyze data from multiple locations such as internal data stores like portfolio, actuarial, and risk management systems as well as petabytes of data from third-party data sources, such as historical securities prices from stock exchanges. With FinSpace, customers can store, catalog, and prepare data at scale, reducing the time it takes to gain insights from from months to minutes. The new APIs are available via the AWS SDK and CLI. To see more details on the Entitlements APIs, see the [Amazon FinSpace Data API Reference.](https://docs.aws.amazon.com/finspace/latest/data-api/fs-api-operations-by-topic.html#fs-api-users-permissions) To get started with Amazon FinSpace, please see the AWS Amazon FinSpace [product page](https://aws.amazon.com/finspace/) and service [documentation](https://docs.aws.amazon.com/finspace/).

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/06/amazon-finspace-apis-assign-granular-user-permissions/