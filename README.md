# Dalux Sync Power Platform Connector [![GitHub](https://img.shields.io/github/license/LogiqApps-AS/dalux-sync-power-platform-connector?style=flat-square)](LICENSE)

Welcome to the Dalux Sync Power Platform Connector! This project includes a solution featuring a custom connector component representing Dalux API for Power Platform (Power Automate).

## 🌟 Overview

The Dalux Sync Power Platform Connector serves as a bridge between Dalux's construction management solutions and Microsoft's Power Platform. This connector enables users to automate tasks, streamline processes, and improve productivity by connecting the Dalux API with Power Automate workflows.

Currently, we support the Dalux Build API v4.7. For more details, refer to the [Dalux Build API v4.7 documentation](https://app.swaggerhub.com/apis/Dalux/DaluxBuild-api/4.7).

## 🚀 Releases

The latest version of the Dalux Sync Power Platform Connector can be found on [GitHub Releases](https://github.com/LogiqApps-AS/dalux-sync-power-platform-connector/releases).

### How to build a new release?

Follow these steps to manually create a new release on GitHub:
1. Create a New Tag: Use the naming convention `v.x.x.x`, where x is a digit. For example: v.1.0.0.
2. Determine the Build Number: The final version of the solution will be v.1.1.0.buildNumber, where `buildNumber` corresponds to `github.run_number`.
3. Generate Artifacts: Ensure that the artifact name is automatically derived from `package/Other/Solution.xml` using the `UniqueName` attribute.
4. Update Documentation: Make sure all relevant documentation is up-to-date with the new release details.
5. Publish the Release: On GitHub, draft a new release, add the appropriate tag, and upload the managed and unmanaged solution files.

## 📦 Artifacts

Artifacts generated during the release process include two types of solutions:
- Managed: This contains the finalized version of the connector, which is ready for deployment. It ensures that all customizations are locked and can be used in production environments.
- Unmanaged: This includes the editable version of the connector for further development and customization. It is ideal for testing and development environments.

## ✨ Future Plans

We plan to extend support to Dalux FM API in future releases. Stay tuned for updates to expand the connector's capabilities to include facilities management functionalities.

## 🛠️ Support

Thank you for using the Dalux Sync Power Platform Connector! If you have any questions or encounter any issues, please feel free to reach out through the following channels:
- GitHub Issues: Report bugs or request features on the GitHub Issues page.
- Repository Contributors: Connect with the repository contributors for additional support.

## 🤝 Contribute

### How can you contribute?

One of the simplest ways to contribute is by engaging in discussions on GitHub issues. Additionally, you can help by submitting pull requests with code enhancements. Remember to star this project on GitHub to show your support. Help spread the word by blogging about the Dalux Sync Power Platform Connector or sharing it on social media.

## 📝 License

This project is licensed under the [MIT license](LICENSE).
