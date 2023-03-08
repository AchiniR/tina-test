---
overview_heading1: Developer Self-Service DevOps Platform
overview_content1: |-
  ### Deploy An Application To Multiple Kubernetes Clusters In Minutes With Basic Kubernetes Knowledge

  App Director hides the complexity of Kubernetes by enabling developers to be productive with Kubernetes from day one.  Application onboarding wizard, Templates, built-in CI tasks allows an application and it’s CI/CD  to be set up on to multiple kubernetes clusters in minutes with minimal knowledge on Kubernetes while promoting automation and reducing operator errors.

  You can point to a git repo and **Containerize** & **Deploy** an Application to _multiple Kubernetes clusters_ within minutes without writing a single line of YAML and only requires very basic knowledge of kubernetes.
overview_features:
- Deploy your apps to multiple Kubernetes clusters.
- Manage multiple environments on different Kubernetes clusters.
- Manage multiple environments on different Kubernetes clusters.
overview_video1_thumbnail: "/images/deploy-multiple-aks-cover.png"
overview_content2: "The Randoli App Director® Platform has two components. \n\nApp
  Director® Console - A multi tenant SaaS application that provides a single-pane-of-glass
  across multiple Kubernetes clusters to containerize, deploy, scale & manage applications.
  It allows you to move from source code to image, deployed on Kubernetes via a guided
  wizard with a few simple steps. You could organize your applications by Projects
  with Identity and Access Management to support multiple teams.\n\nApp Director®
  Agent - that connects with the App Director® Platform to receive deployments and
  send back events. The agent is managed via an Operator and can be scoped to one
  or more namespaces or cluster-wide."
overview_heading2: How the App Director® Platform Works
overview_video_1_link: https://youtu.be/aYbgPz8BjQ0
overview_video2_thumbnail: "/images/overview-video-img2.png"
overview_video_2_link: ''
overview_video_3_link: ''
overview_heading3: Build Tekton Pipelines With Built-In & BYO tasks In Minutes
overview_content3: |
  Build cloud-native Tekton pipelines via templates or from scratch using a guided wizard. We provide built-in tasks as well as allow you to bring your own tasks.
  We provide the following tekton tasks out-of-the-box

  - Build From Source / From Image Registry / Build From Dockerfile
  - Scan Source (Sonarqube)
  - Build Image
  - Scan Image (Stackrox - Roadmap item)
  - Tag Image
  - Deploy Image
  - Invoke Webhook
overview_heading4: Containerize your applications from source using S2I or Cloud Native
  Buildpacks
overview_content4: "Source to Image (S21) support for \n- Java\n- Node.js\n- Angular,
  React and Vue\n \nCloud-Native build packs support for the following via Paketo
  & Heroku buildpacks\n- Java\n- Node.js\n- Python\n- .NET\n- Ruby\n- Golang\n- Angular,
  React and Vue"
overview_heading3_image: "/images/overview-img.png"
overview_video3_thumbnail: "/images/overview-video-img1.png"
overview_heading5: Single Pane-Of-Glass Across Multi Clusters/Cloud Vendors
overview_content5: "With many organizations increasing using multi cluster/cloud strategies
  and teams treating K8s clusters as cattle (instead of pets) it's imperative to provide
  your developers with a simplified approach to be successful when deploying applications
  across multiple clusters.\n\nApp Director provides a simplified Application Centric
  view (not infrastructure centric) across multiple kubernetes clusters with any cloud
  vendor.\nIt provides a single point-of-view for pipeline logs & events across multiple
  environments  (subject to RBAC and cluster/environment access) allowing the developers
  one console to work with, instead of having to log into multiple cluster consoles. "
overview_video_thumbnail_5: "/images/overview_cicd.png"
overview_video_link_5: ''
overview_image4_thumbnail: "/images/overview-video-img1.png"
overview_video4_thumbnail: "/images/overview-video-img1.png"
app-director-image-content-section:
- title: Build Tekton Pipelines With Built-In & BYO tasks In Minutes
  content: |-
    Build cloud-native Tekton pipelines via templates or from scratch using a guided wizard. We provide built-in tasks as well as allow you to bring your own tasks.

    * We provide the following tekton tasks out-of-the-box
    * Build From Source / From Image Registry / Build From Dockerfile
    * Scan Source (Sonarqube)
    * Build Image
    * Scan Image (Stackrox - Roadmap item)
    * Tag Image
    * Deploy Image
    * Invoke Webhook
  image:
  - "/images/build-tekton-pipelines-cover.png"
  video_link: https://www.youtube.com/watch?v=2ArWJa3FJLY
  background_color: "#FFFFFF"
- title: Containerize your applications from source using S2I or Cloud Native Buildpacks
  content: "App Director provides several source -to-image options for containerizing
    your applications by simply pointing to a git repo. _Please note your source code
    is downloaded and built on your own kubernetes clusters and NOT on the Randoli
    App Director side_.\n\nYour App Director admin user can choose from the following
    options for each language. This can not be modified by other users to ensure uniformity
    and compliance with the standards chosen by the admin user.\n\n* Red Hat S2I ([read
    more](https://github.com/openshift/source-to-image)) ![open-in-new](/images/vector.png
    \"open-in-new\") \n* Paketo cloud-native buildpacks ([read more](https://paketo.io/))
    \ ![open-in-new](/images/vector.png \"open-in-new\") \n* Heroku cloud-native buildpacks
    ([read more](https://devcenter.heroku.com/articles/buildpacks)) ![open-in-new](/images/vector.png
    \"open-in-new\") "
  image:
  - "/images/language.svg"
  video_link: ''
  background_color: "#FFFFFF"
- title: Single Pane-Of-Glass Across Multi Clusters/Cloud Vendors
  content: |-
    With many organizations increasing using multi cluster/cloud strategies and teams treating K8s clusters as cattle (instead of pets) it's imperative to provide your developers with a simplified approach to be successful when deploying applications across multiple clusters.

    App Director provides a simplified Application Centric view (not infrastructure centric) across multiple kubernetes clusters with any cloud vendor.

    It provides a single point-of-view for pipeline logs & events across multiple environments  (subject to RBAC and cluster/environment access) allowing the developers one console to work with, instead of having to log into multiple cluster consoles.
  image:
  - "/images/multi-cluster.png"
  video_link: ''
  background_color: "#FFFFFF"
core_features:
- icon: "/images/ic-application-wizard.svg"
  title: Application Onboarding Wizard
  details: A guided approach to deploying applications based on best practices recipes
    and guard rails allowing developers to be productive with little to no Kubernetes
    knowledge.
  description: ''
- icon: "/images/ic-template-catalogue.svg"
  title: Templates For Applications & Environments
  details: Templates & template catelogue allows organizations and teams to share
    best practices recipes and enforce standards while promoting automation and reusability
    across teams.
  description: ''
- icon: "/images/ic-single-pane.svg"
  title: Single Pane-Of-Glass Across Multi Clusters/Vendors
  details: Unified interface across multiple k8s clusters, on-prem or cloud with any
    vendor, allowing developers one console to work with, instead of having to log
    into multiple cluster consoles.
  description: Lorem Ipsum is simply dummy text of the printing and typesetting industry.
    Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
    when an unknown printer took a galley of type and scrambled it to make a type
    specimen book. It has survived not only five centuries, but also the leap into
    electronic typesetting, remaining essentially unchanged. It was popularised in
    the 1960s with the release of Letraset sheets containing Lorem Ipsum passages,
    and more recently with desktop publishing software like Aldus PageMaker including
    versions of Lorem Ipsum.
- icon: "/images/ic-cloud-native.svg"
  title: Cloud Native Buildpacks & s2i
  details: Cloud-Native buildpacks and s2i (Source-to-Image) support for Java, Node.js,
    Python, .NET, Ruby, Golang, Angular, React and Vue
  description: ''
- icon: "/images/ic-cloud-tekton.svg"
  title: Cloud-Native CI via Tekton
  details: Build cloud-native Tekton pipelines via templates or build from scratch
    using a guided wizard. We provide built-in tasks or you can bring your own.
  description: '"It is a long established fact that a reader will be distracted by
    the readable content of a page when looking at its layout. The point of using
    Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed
    to using ''Content here, content here'', making it look like readable English.
    Many desktop publishing packages and web page editors now use Lorem Ipsum as their
    default model text, and a search for ''lorem ipsum'' will uncover many web sites
    still in their infancy. Various versions have evolved over the years, sometimes
    by accident, sometimes on purpose (injected humour and the like).\n\n"'
- icon: "/images/ic-git-tops.svg"
  title: GitOps Ready CD
  details: GitOps ready with integrations to Gitlab, Github & Bitbucket allowing you
    to mange CD with your choice of GitOps operator
  description: ''
- icon: "/images/ic-security.svg"
  title: Security
  details: We provide Built-in IAM, SSO via OpenID Connect, Audit Logs, Built-in Let's
    Encrypt support for TLS via CertManager,  ability to link application configuration
    managed by your teams outside of App Director
  description: The standard chunk of Lorem Ipsum used since the 1500s is reproduced
    below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum
    et Malorum" by Cicero are also reproduced in their exact original form, accompanied
    by English versions from the 1914 translation by H. Rackham.
- icon: "/images/ic-faster-feedback.svg"
  title: Faster Feedback Loop
  details: Provides pipeline logs & kubernetes events for an application in a single
    console. If a container restarts we capture the last 100 lines of the previous
    instance for easy debugging.
  description: ''
- icon: "/images/ic-cost-allocation.svg"
  title: Cost Allocation For Teams/Projects
  details: App Director provides a simplified costing model per project based on CPU
    & Memory allocation, itemized by cluster.   This allows organizations and teams
    a basis to apportion costs to applications and projects as well as chargeback
    model between internal teams.
  description: Provides a simplified costing model per project based on CPU & Memory
    allocation, itemized by cluster.
title: app-director-overview
app_director_overview_heading: The Modern DevSecOps Platform for Kubernetes
app_director_overview_description: A platform engineering solution to improve your
  speed to market through cloud native CI, CD, actionable insights, golden paths &
  developer self-service and reduces the burden on DevOps teams
app_director_overview_video_link: https://youtu.be/pFC2UZf0O4o
app_director_overview_video_cover_image: "/images/app_director_conceptual_website_5.png"
app_director_overview_button_text: Book a Demo
key_feature_section:
  title: A DevSecOps Solution Bringing Simplicity, Speed and Scale
  content: App Director is a vendor neutral internal developer platform. App Director
    reduces the burden on DevOps teams by automating repetitive tasks, and provides
    speed, best practices and security for developers through the use of golden paths.
    The solution works on-prem, cloud or hybrid and with any K8s cluster.
  image: "/images/structured-view.jpg"
app_director_overview_benefits_text: Key Benefits
app_director_overview_for_section:
  title: Who is App Director For?
  reasons:
  - title: Developers
    icon: "/images/overview_for_section_developers.svg"
    content: |-
      * Shift left (test early and detect early)
      * Golden paths provide speed and confidence
      * Deploy to Kubernetes with minimal knowledge
      * View build and deployment feedback
  - title: DevOps / Platform Engineering
    content: |-
      * Automate repetitive tasks
      * Create golden paths
      * Organization-wide CI / CD settings
      * Single pane of glass
      * Identity & access management and audit log
      * CI / CD and cloud native integrations
    icon: "/images/overview_for_section_devops.svg"
  - title: Management
    content: |-
      * Empower developers with k8s superpowers
      * Apply organization best practices and standards
      * Support for software supply chain risk mitigation
      * Visibility into costing and change management
    icon: "/images/overview_for_section_management.svg"
core_feature_section:
  heading: Core Features
  core_features:
  - name: Golden Paths for Applications & Environments
    description: Templates allow organizations and teams to share best practices recipes
      and enforce standards while promoting speed, automation and reusability across
      teams.
    image: "/images/ic-template-catalogue-1.svg"
  - name: Shift Left
    description: View pipeline logs, kubernetes events and integrations into image
      and source code scanning for an application in a single console
    image: "/images/ic-faster-feedback.png"
  - name: Application Onboarding Wizard
    description: A guided approach to deploying applications based on best practices
      recipes and guard rails allowing developers to quickly be productive with minimal
      Kubernetes knowledge.
    image: "/images/ic-application-wizard-1.svg"
  - name: Single Pane-Of-Glass Across Multi Clusters/Vendors
    description: Unified interface across multiple k8s clusters, on-prem or cloud
      with any vendor, allowing developers one console to work with
    image: "/images/ic-single-pane-1.svg"
  - name: Security
    description: We provide Built-in IAM, SSO via OpenID Connect, Audit Logs, Built-in
      Let's Encrypt support for TLS via CertManager, ability to link application configuration
      managed by your teams outside of App Director
    image: "/images/ic-security-1.svg"
  - name: Cloud Native Buildpacks & S2I
    description: Securely and quickly containerize an image from source code through
      your favourite development languages (Java, Node.js, Python, .NET, Ruby, Golang,
      Angular, React and Vue)
    image: "/images/ic-cloud-native-1.svg"
  - name: Cloud-Native CI via Tekton
    description: Build cloud-native Tekton pipelines via templates or build from scratch
      using a guided wizard. Use our built-in tasks or bring your own.
    image: "/images/ic-cloud-tekton-1.svg"
  - name: GitOps Ready CD
    description: GitOps ready with integrations to Gitlab, Github & Bitbucket allowing
      you to manage CD with your choice of GitOps operator
    image: "/images/ic-git-tops-1.svg"
  - name: Cost Allocation For Teams/Projects
    description: View a simplified costing model per project based on CPU & memory
      allocation, itemized by cluster
    image: "/images/ic-cost-allocation-1.svg"
bottom_image: "/images/simplicity_speed_scale.png"

---
