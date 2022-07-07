## Explore wind speed images from Amazon Sustainability Data Initiative (ASDI) hosted on S3 using SageMaker Studio Lab (SMSL)

This sample explores some free, accessible data hosted on AWS S3 under the Amazon Sustainability Data Initiative (ASDI), and analyzes it in AWS Sagemaker Studio Lab.

The Amazon Sustainability Data Initiative (ASDI) seeks to accelerate sustainability research and innovation by minimizing the cost and time required to acquire and analyze large sustainability datasets. ASDI supports innovators and researchers with the data, tools, and technical expertise they need to move sustainability to the next level.

This sample notebook works with satellite imagery stored in S3. The imagery is a collection of single band pictures of hurricanes at sea.

The data is provided by [Radiant Earth](https://www.radiant.earth/) under the Creative Commons Attribution 4.0 International license, and hosted, for free, in Amazon S3 under the [Amazon Sustainability Data Initiative](https://sustainability.aboutamazon.com/environment/the-cloud/asdi) catalog.

- In this sample, I show how to connect to S3, fetch some data from a specific storm, and visualize the change of a storm's appearance over time.
- Thank you, and congratulations to the [winners of the challenge](https://drivendata.co/blog/wind-dependent-variables-winners/) for which this data was first generated, and for [resources created by Tamara Glazer,](https://github.com/radiantearth/mlhub-tutorials/blob/main/notebooks/NASA%20Tropical%20Storm%20Wind%20Speed%20Challenge/nasa-tropical-storm-wind-speed-challenge-benchmark.ipynb) on which parts of this sample were based.
- You can use Sage MakerStudio Lab to run this example showing how to extract information from sustainability-relevant open data hosted on AWS.

[![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/https://github.com/aws-samples/asdi-smsl-wind-speed-data/blob/main/wind-speed-data.ipynb)
## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License Summary

The documentation is made available under the Creative Commons Attribution-ShareAlike 4.0 International License. See the LICENSE file.

The sample code within this documentation is made available under the MIT-0 license. See the LICENSE-SAMPLECODE file.
