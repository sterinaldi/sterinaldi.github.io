---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
title: "Papers"
button_name: "Papers"
# for override side_and_top_nav_buttons in _data/conf/main.yml
icon: "fa fa-file-o"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# if you enabled image_viewer_posts you don't need to enable this. This is only if image_viewer_posts = false
#image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Papers (and other useful stuff)"
    info: "Here you find the short-author papers I contributed to as well as some useful resources."
    
  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "CV and publications"
      type: id_files
      color: "lightblue"
    - title: "Papers"
      type: id_papers
      color: "#F4A273"
    - title: "Resources"
      type: id_resources
      color: "#62b462"

  list:
    # Sample
    - type: id_programming
      title: "Stack OverFlow"
      url: "https://stackoverflow.com/"
      info: "Stack Overflow is a question and answer website for professional and enthusiastic programmers."
    # CV and publications
    - type: id_files
      title: "CV"
      url: "https://drive.google.com/file/d/1WVY_1FJnrC0IQ7g6cJfDONJbhgB0aiWb/view?usp=sharing"
      info: "Curriculum Vitae"
    - type: id_files
      title: "Publications"
      url: "https://drive.google.com/file/d/1ZiXOgMESvgaIapnbAcjFHSExyPbGDhPa/view?usp=sharing"
      info: "List of publications"
    - type: id_files
      title: "ADS"
      url: "https://ui.adsabs.harvard.edu/search/q=((%20author%3A%22Rinaldi%2C%20Stefano%22)%20AND%20year%3A2021-)&sort=date%20desc%2C%20bibcode%20desc&p_=0"
      info: "Complete list of publications on ADS"
      
    # Papers
    
    - type: id_papers
      title: "Rinaldi & Ramírez-Tannus. (2024)"
      url: "https://www.aanda.org/articles/aa/full_html/2024/12/aa51694-24/aa51694-24.html"
      info: "Non-parametric identification of single-lined binary candidates in young clusters using single-epoch spectroscopy"
      
    - type: id_papers
      title: "Ng et al. (2024)"
      url: "https://arxiv.org/pdf/2410.23541"
      info: "Inferring cosmology from gravitational waves using non-parametric detector-frame mass distribution"

    - type: id_papers
      title: "Poon et al. (2024)"
      url: "https://arxiv.org/pdf/2406.06463"
      info: "Galaxy lens reconstruction based on strongly lensed gravitational waves: similarity transformation degeneracy and mass-sheet degeneracy"

    - type: id_papers
      title: "Rinaldi & Del Pozzo (2024)"
      url: "https://inspirehep.net/files/b3388867df58d50236f31d138b3c1adc"
      info: "FIGARO: hierarchical non-parametric inference for population studies"

    - type: id_papers
      title: "Rinaldi et al. (2024b)"
      url: "https://arxiv.org/pdf/2405.07504"
      info: "Hierarchical inference of evidence using posterior samples"
      
    - type: id_papers
      title: "Rinaldi (2024)"
      url: "https://arxiv.org/pdf/2405.06366"
      info: "Accounting for selection biases in population analyses: equivalence of the in-likelihood and post-processing approaches"

    - type: id_papers
      title: "Iorio et al. (2024)"
      url: "https://arxiv.org/pdf/2404.17568"
      info: "The boring history of Gaia BH3 from isolated binary evolution"

    - type: id_papers
      title: "Rinaldi et al. (2024a)"
      url: "https://www.aanda.org/articles/aa/full_html/2024/04/aa48161-23/aa48161-23.html"
      info: "Evidence of evolution of the black hole mass function with redshift"

    - type: id_papers
      title: "Dotti et al. (2023)"
      url: "https://www.aanda.org/articles/aa/pdf/2023/12/aa46916-23.pdf"
      info: "A fast test for the identification and confirmation of massive black hole binaries"

    - type: id_papers
      title: "Morton et al. (2023)"
      url: "https://arxiv.org/pdf/2310.16025.pdf"
      info: "GW190521: a binary black hole merger inside an active galactic nucleus?"

    - type: id_papers
      title: "Sgalletta et al. (2023)"
      url: "https://academic.oup.com/mnras/article/526/2/2210/7273849"
      info: "Binary neutron star populations in the Milky Way"

    - type: id_papers
      title: "Rinaldi et al. (2023)"
      url: "https://link.springer.com/content/pdf/10.1140/epjc/s10052-023-12078-6.pdf"
      info: "Systematic errors in the determination of the constant of gravitation"
      
    - type: id_papers
      title: "Cheung et al. (2023)"
      url: "https://arxiv.org/pdf/2308.12182.pdf"
      info: "Mitigating the effect of population model uncertainty on strong lensing Bayes factor using nonparametric methods"

    - type: id_papers
      title: "Rinaldi & Del Pozzo (2022b)"
      url: "https://academic.oup.com/mnrasl/article/517/1/L5/6692889?guestAccessKey=7e2d2a70-4c72-471a-8445-e4e074249867"
      info: "Rapid localization of gravitational wave hosts with FIGARO"

    - type: id_papers
      title: "Mastrogiovanni et al. (2022)"
      url: "https://onlinelibrary.wiley.com/doi/epdf/10.1002/andp.202200180"
      info: "Cosmology with Gravitational Waves: a review"

    - type: id_papers
      title: "Rinaldi & Del Pozzo (2022a)"
      url: "https://academic.oup.com/mnras/article/509/4/5454/6424929?guestAccessKey=896e80a6-fb67-4910-99dd-bbc0256126ee"
      info: "(H)DPGMM: a hierarchy of Dirichlet process Gaussian mixture models for the inference of the black hole mass function"

    - type: id_papers
      title: "Mastrogiovanni et al. (2021)"
      url: "https://arxiv.org/pdf/2103.14663.pdf"
      info: "On the importance of source population models for gravitational-wave cosmology"

    # Resources
    
    - type: id_resources
      title: "Demoblack group"
      url: "https://demoblack.com"
      info: "The Demoblack group in Padova/Heidelberg"
      
    - type: id_resources
      title: "RayNest"
      url: "https://github.com/wdpozzo/raynest"
      info: "Parallel nested sampling in Python"
      
    - type: id_resources
      title: "FIGARO"
      url: "https://github.com/sterinaldi/figaro"
      info: "Multivariate probability density estimator"

    - type: id_resources
      title: "Conjugate priors"
      url: "https://www.cs.ubc.ca/~murphyk/Papers/bayesGauss.pdf"
      info: "Everything you need to know about the conjugate priors to the Gaussian distribution"
---
