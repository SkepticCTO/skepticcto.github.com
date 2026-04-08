# SkepticCTO: Decoding the Language Machine

Welcome to the official repository for **SkepticCTO**, the companion website for the AI educational series *"Decoding the Language Machine."*

## Links
* **Website:** [https://www.skepticcto.com/](https://www.skepticcto.com/)
* **YouTube Channel:** [https://www.youtube.com/@skepticcto](https://www.youtube.com/@skepticcto)

## Purpose
This repository houses the source code for the SkepticCTO website. It is designed to be a clean, fast, and accessible hub for articles, deep dives, and educational resources regarding Artificial Intelligence and the technology behind large language models. 

The site is built as a static website using **Jekyll**, styled with the **Minima 3.0** theme (using the `auto` dark/light skin), and is deployed automatically to GitHub Pages via **GitHub Actions**.

## Local Development Setup

To preview or edit the site locally, you will need a Ruby development environment. These instructions are tailored for **Ubuntu/WSL**, but the concepts apply to macOS and other Linux distributions.

### 1. Install Prerequisites
Ensure you have Ruby and the necessary build tools installed on your system.
```bash
sudo apt update
sudo apt install ruby-full build-essential zlib1g-dev -y
```

### 2. Configure Local Gem Installation
To avoid permission errors, configure your environment to install Ruby gems locally rather than globally via `sudo`. Add these lines to your `~/.bashrc` (or `~/.zshrc`):
```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

### 3. Install Bundler
Bundler is the dependency manager used to ensure the local environment perfectly matches the GitHub Pages deployment.
```bash
gem install bundler jekyll
```

### 4. Run the Site Locally
Clone this repository, navigate into the directory, and install the project dependencies from the `Gemfile.lock`:
```bash
# Clone the repository
git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
cd YOUR-REPO-NAME

# Install required gems (including Minima 3.0)
bundle install

# Build and serve the site locally
bundle exec jekyll serve
```
The site will now be available in your browser at `http://127.0.0.1:4000/`.

## Resources & Documentation
To learn more about the tools powering this site, refer to the following official documentation:
* [Jekyll Official Documentation](https://jekyllrb.com/docs/)
* [Minima Theme Repository & Guide](https://github.com/jekyll/minima)
* [Bundler Documentation](https://bundler.io/)
* [GitHub Actions for GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages)
