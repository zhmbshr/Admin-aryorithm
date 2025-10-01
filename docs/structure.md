Excellent question. Moving away from subdomains and consolidating everything under the main `aryorithm.com` domain is a very strong strategy. It simplifies your technical overhead and concentrates all of your brand authority and SEO value into a single domain.

The best way to do this is by using **top-level directories** to create clear, logical sections for each product.

Here is the recommended structure.

### The Core Principle

Your products, XTtorch and XInfer, will be treated as major sections of the main website, each living in its own folder.

*   `aryorithm.com/xtorch/`
*   `aryorithm.com/xinfer/`

This approach is clean, intuitive for users, and excellent for search engines.

---

### Visual Schematic of the New Site Structure

Here is a visual tree representing the entire website layout under `aryorithm.com`.

```
aryorithm.com
├── /                           (Main Homepage)
├── /about
├── /blog
│   ├── /post-1-title
│   └── /post-2-title
├── /contact
│
├── /xtorch/                    (XTtorch Product Homepage)
│   └── /docs/
│       ├── /getting-started
│       ├── /tutorials
│       └── /api-reference
│
└── /xinfer/                    (XInfer Product Homepage)
    ├── /docs/
    │   ├── /library/           (Docs for the C++ Library)
    │   │   ├── /getting-started
    │   │   └── /api-reference
    │   └── /cloud-api/         (Docs for the Cloud API)
    │       ├── /quickstart
    │       └── /authentication
    │
    └── /hub/                     (Ignition-Hub Homepage)
        ├── /engines              (Engine Download Library)
        ├── /login
        ├── /signup
        └── /dashboard            (For logged-in users)
            └── /models
            └── /billing
```

---

### Detailed Breakdown of the Structure

#### **1. Main Company Site (The "Root")**
These pages represent your corporate identity.
*   **`aryorithm.com/`**: The main homepage you've already designed.
*   **`aryorithm.com/about`**: Your "About Us" page.
*   **`aryorithm.com/blog`**: The index for your blog posts.
*   **`aryorithm.com/contact`**: Your contact page.

#### **2. The XTtorch Section (`/xtorch/`)**
This directory contains everything related to the XTtorch library.
*   **`aryorithm.com/xtorch/`**: This is the **new homepage for XTtorch**. It's the landing page that introduces the library, shows the "before & after" code, lists features, etc.
*   **`aryorithm.com/xtorch/docs/`**: The main landing page for all XTtorch documentation.
*   **`aryorithm.com/xtorch/docs/getting-started`**: The installation and setup guide.
*   **`aryorithm.com/xtorch/docs/api-reference`**: The detailed, searchable API documentation.

#### **3. The XInfer Section (`/xinfer/`)**
This directory contains everything for the XInfer ecosystem (library, cloud, and hub).
*   **`aryorithm.com/xinfer/`**: This is the **new homepage for XInfer**. It introduces both the C++ library and the Cloud API.
*   **`aryorithm.com/xinfer/docs/`**: The main landing page for all XInfer documentation. Notice how we create sub-folders inside to keep the C++ and Cloud docs separate but organized.
    *   **`aryorithm.com/xinfer/docs/library/getting-started`**: For the C++ library.
    *   **`aryorithm.com/xinfer/docs/cloud-api/quickstart`**: For the REST API.
*   **`aryorithm.com/xinfer/hub/`**: This is the homepage for your **Ignition-Hub**. It's the central point for your cloud service and engine downloads.
    *   **`aryorithm.com/xinfer/hub/engines`**: The page for downloading pre-built models.
    *   **`aryorithm.com/xinfer/hub/dashboard`**: The mission control center for logged-in cloud users.

### Why This Structure is Better

1.  **Unified Brand Authority:** Every page and every link contributes to the strength of one single domain: `aryorithm.com`. This is a significant advantage for SEO.
2.  **Simplicity:** You only have one website to manage, one SSL certificate to maintain, and one analytics account to monitor.
3.  **Clear Navigation:** The URL structure is logical and tells the user exactly where they are. `aryorithm.com/xinfer/docs/library/` is perfectly clear.
4.  **Scalability:** If you create a third product called "XDeploy," you simply add a new `/xdeploy/` directory. The pattern is clean and easy to extend.