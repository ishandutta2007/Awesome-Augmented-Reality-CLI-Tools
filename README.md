# Awesome-Augmented-Reality-CLI-Tools

## Top Augmented Reality & CLI Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on WebXR Frameworks, Marker/Image Tracking & Self-Hosted AR Tooling*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Augmented Reality & CLI Tools**. These tools help developers build browser-based AR experiences, track images or markers, and integrate AR into web applications—covering everything from commercial WebAR platforms to open-source JavaScript libraries and command-line build tooling.

**Examples** include 8th Wall, ZapWorks, Blippar, PTC Vuforia, AR.js, MindAR, A-Frame, and model-viewer (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted WebAR, open-source tracking libraries, and community-driven AR frameworks—ideal for developers seeking full control over their AR pipeline, avoiding per-view or per-scan SaaS fees, and building experiences that run entirely in the browser without proprietary SDKs. The open-source landscape is genuinely functional: **AR.js** provides marker, image, and location-based tracking in a lightweight package [citation:1], **MindAR** offers image and face tracking with A-Frame and Three.js integrations [citation:8], and **model-viewer** makes rendering interactive 3D models with optional AR as easy as an `<img>` tag [citation:9].

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global augmented reality market is estimated at approximately $120B–$140B in 2025 and projected to surpass $160B–$210B in 2026, registering an annual growth rate (CAGR) of 25%–35%. The market exhibits a bifurcated concentration: it is moderately concentrated at the foundational platform, operating system, and spatial hardware level dominated by tech giants (Meta, Apple, Google, PTC), yet highly fragmented across specialized authoring SaaS platforms, independent software vendors (ISVs), WebAR toolkits, and vertical industrial solutions.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Pricing (Starting Tier) | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[PTC Vuforia](https://www.ptc.com/en/products/vuforia)** | ~$20.8B–$22.1B Market Cap / $2.74B Annual Revenue (PTC Inc.) | $99/month (Cloud Recognition Plus add-on); custom annual quote for Premium/Enterprise | **Free Forever (Basic Plan)**: Unlimited app development and commercial deployment without watermarks for core features (Image Targets, Multi-Targets, Cylinder Targets, VuMarks, Ground Plane); includes up to 1,000 cloud-stored images and 1,000 cloud recognitions/month. | Enterprise AR platform with robust image and object tracking. Vuforia Engine powers mobile and WebAR tracking pipelines. |
| **[8th Wall](https://www.8thwall.com/)** | ~$3.5B Acquisition Valuation / >$1B Annual Revenue (Niantic / Niantic Spatial) | $0/month (100% Free Open-Source model; historically started at $300/month or $99/month Pro) | **Free Forever (Current Open-Source Model)**: Core engine, desktop tools, and self-hosted WebAR SDK released 100% free with no project caps, fees, or hosted subscription tiers. *(Historical Free Trial: 14-day trial with unpublishable test projects).* | WebAR platform with SLAM, image targets, and face effects, now transitioning developers toward free self-hosted WebAR infrastructure. |
| **[ZapWorks](https://zap.works/)** | $45M Acquisition Valuation / ~$5.1M Annual ARR (Zappar / Infinite Reality) | $65/month (billed annually) or $99/month (billed monthly) for Pro tier | **14-day Free Trial** for paid Pro workspace; or **Free Developer Plan (Non-Commercial)**: unlimited projects and views strictly for non-commercial use, with Zappar branded interstitial splash screen, ~25MB project size limit, and 250 AI credits/month. | Full-stack AR creation platform with visual editors (Designer, Mattercraft, Studio) and Universal AR SDKs with image tracking and WebAR hosting. |
| **[Blippar](https://www.blippar.com/)** | ~$5M Post-Restructure Extension / ~$5M–$8M ARR (Candy Ventures) | £7.99/month (~$10/month) for Creative plan; £100/month for WebAR SDK | **Free Forever (Starter Plan)**: Unlimited project creation and internal testing in Design Canvas/Hub, but no live public publishing; or **14-day Free Trial** on paid publishing tiers. | No-code AR creation platform (Blippbuilder) and WebAR SDK with marker and image tracking positioned for marketing and interactive campaigns. |

## Open-Source GitHub Projects

- **[AR.js](https://github.com/AR-js-org/AR.js)**  
  **The most widely adopted open-source WebAR library for marker, image, and location-based tracking.** **MIT licensed**, lightweight JavaScript. **Three tracking modes**: Marker-based (scan a Hiro marker), Image Tracking (scan a custom image), and Location-based (GPS coordinates). **Works with A-Frame and Three.js**—the A-Frame build lets you create AR in ~10 lines of HTML [citation:1]. **Active maintenance** by the AR.js org.

- **[MindAR](https://github.com/hiukim/mind-ar-js)**  
  **Open-source image and face tracking library written in pure JavaScript.** **Utilizes WebGL via TensorFlow.js and Web Workers** for high performance in the browser. **A-Frame and Three.js integrations** included. **Target Images Compiler** lets you compile custom images into `.mind` files via a browser-based tool [citation:8]. **The only actively maintained open-source WebAR SDK** offering features comparable to commercial alternatives [citation:13].

- **[A-Frame](https://github.com/aframevr/aframe)**  
  **Web framework for building virtual reality and AR experiences.** **MIT licensed**, **17,122 GitHub stars**. **HTML-based**—compose 3D scenes with declarative markup. **ECS architecture**, works with AR.js and MindAR for AR experiences [citation:4]. **Best for developers wanting a declarative, HTML-first approach** to WebAR.

- **[model-viewer](https://github.com/google/model-viewer)**  
  **Google's web component for rendering interactive 3D models with optional AR.** **Makes adding AR to a page as easy as an `<img>` tag**—just set the `src` to a glTF/GLB file [citation:9]. **Supported on last 2 major versions of all evergreen browsers**. **Best for product visualization and simple "view in your space" AR** without full tracking logic.

- **[ARnft](https://github.com/webarkit/ARnft)**  
  **Small JavaScript library for WebAR with Natural Feature Tracking (NFT).** Part of the WebARKit ecosystem. **Best for image tracking** without the full weight of AR.js.

### Additional Strong Open-Source Options

- **[PlayCanvas AR](https://github.com/playcanvas/playcanvas-ar)** — Fast and easy AR for the web, built on the PlayCanvas engine [citation:7].
- **[Simple-AR](https://github.com/akbartus/Simple-AR)** — Web-based image tracking library based on WebAssembly, compatible with A-Frame, Babylon.js, and Three.js [citation:7].
- **[encantAR.js](https://github.com/alemart/encantar-js)** — GPU-accelerated Augmented Reality for the web, device-agnostic [citation:7].
- **[awesome-WebAR](https://github.com/tobiasbueschel/awesome-WebAR)** — Curated list of WebAR projects, resources, and tools [citation:7].

**Frameworks for building custom systems**: Combine **MindAR** for robust image/face tracking, **A-Frame** for declarative scene composition, and **model-viewer** for simple 3D product previews. For marker-based AR, **AR.js** remains the lightest path to a working demo.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- WebAR experiences require camera access and may raise privacy concerns; ensure user consent and avoid capturing sensitive environments. AR tracking accuracy varies by device and lighting conditions.
- **Tool choice depends on whether you need marker tracking, image tracking, or simple 3D preview.** **AR.js is the lightest entry point for marker-based AR** and supports image and location tracking [citation:1]. **MindAR is the only actively maintained open-source SDK with image and face tracking comparable to commercial alternatives** [citation:13]. **model-viewer is not a tracking library**—it renders 3D models with an optional AR "view in space" button, best for product pages rather than interactive experiences [citation:9]. **A-Frame is a framework, not an AR library**—it needs AR.js or MindAR to add tracking [citation:4]. Validate whether you need full tracking (AR.js, MindAR) or simple model viewing (model-viewer) before committing.

---

**Made for WebAR developers, creative technologists, and teams building browser-based AR infrastructure.**  
Let's make augmented reality more open, accessible, and web-native.
