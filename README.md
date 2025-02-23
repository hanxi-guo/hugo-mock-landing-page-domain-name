# Configuring a Custom Domain for GitHub Pages

In this repository, I have purchased a custom domain and configured it to point to my GitHub Pages website. This process ensures that my site is accessible via a personalized URL rather than a default GitHub subdomain.

## Domain Registration
- Purchased a domain from *NameCheap*.
- Selected a suitable domain name for the GitHub Pages site.

## Repository Setup
- Imported the previously auto-deployed repository [`hugo-mock-landing-page-autodeployed`](https://github.com/hanxi-guo/hugo-mock-landing-page-autodeployed) into a new repository to maintain version tracking while configuring the domain.
- Configured GitHub Pages to serve the new repository.

## Domain Configuration
- Updated the **CNAME** in [`gh-pages-deployment.yaml`](.github/workflows/gh-pages-deployment.yaml) in the repository to include the custom domain.
- Configured NameCheap DNS settings as its instuction.
- Verified the custom domain configuration in the GitHub Pages settings.

## **Repository Contents**
- `.github/workflows/gh-pages-deployment.yaml` - Automated deployment workflow.

---

## License

This project is licensed under the MIT License.

---

This repository serves as an extension of the previously auto-deployed Hugo website, now enhanced with a custom domain for better accessibility and branding. 🚀

