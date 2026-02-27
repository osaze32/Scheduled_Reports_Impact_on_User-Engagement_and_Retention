### **Business Problem**

CloudMetrics is a B2B SaaS platform that enables businesses to monitor performance through dashboards and reports. Users rely heavily on manually generating reports to track key metrics, requiring repeated effort and consistent logins to stay informed.

Despite steady usage, engagement remains inconsistent, as users depend on manual reporting workflows that introduce friction and limit product stickiness. Following the introduction of Scheduled Reports, it is unclear whether the feature is being adopted, whether it meaningfully reduces manual effort, and whether it drives deeper engagement and retention across different user segments.

### **Key Question**

To what extent has the introduction of Scheduled Reports improved user engagement and retention, and which user segments derive the most value from it?

### **Success Criteria**

The success of Scheduled Reports is evaluated across four dimensions: adoption, engagement, behavior change, and retention. Adoption measures whether users are using the feature, engagement assesses whether users actively consume generated reports, behavior change evaluates the shift from manual to automated reporting, and retention determines whether the feature improves long-term user activity and product stickiness.

### **Dataset Overview**

The dataset captures user activity before and after the introduction of Scheduled Reports, enabling direct measurement of changes in engagement, reporting behavior, and retention. Event-level tracking allows reconstruction of the full feature lifecycle from adoption to consumption.

Key events include:

- login
- report_created (manual reporting behavior)
- report_generated (system output)
- report_scheduled (feature adoption)
- report_viewed (actual user engagement)

The dataset also includes plan segmentation (Free, Pro, Max, Enterprise) and account-level identifiers, allowing analysis across both individual users and enterprise teams.

### **Key Metrics**

**Adoption Rate** – percentage of active users who used Scheduled Reports

**Reports Viewed per User** – average number of reports viewed per active user

**Consumption Rate** – percentage of generated reports that were viewed

**Manual Reports (Pre vs Post)** – comparison of manual reporting before and after feature launch

**Automation Share** – proportion of reports created through scheduling vs manual

**WAU** – number of users logging in weekly

### **Analysis Approach**

- **Feature Adoption** – Measure how many users adopt Scheduled Reports over time and identify which user segments drive adoption.
- **Engagement Analysis** – Evaluate whether users actively consume generated reports using metrics such as reports viewed per user and consumption rate.
- **Behavior Shift Analysis** – Assess whether users transition from manual report creation to automated reporting after the feature launch.
- **Retention Analysis** – Compare retention and activity levels between users who adopt the feature and those who do not to determine its impact on product stickiness.
- **Segment Analysis** – Break down all key metrics by plan type to identify where the feature delivers the most value.

### **Key Insights**

- Scheduled Reports achieved **~21% weekly adoption within the first 6 weeks** and stabilized around that level, indicating **steady but not accelerating uptake** across users.
- Overall adoption reached **45% (~1300 users)**, showing the feature has **broad reach**, though sustained weekly adoption suggests **limited momentum beyond early users**.
- Automation Share stands at **24%**, meaning **manual reporting still dominates**, so the feature has **not yet significantly replaced existing workflows**.
- Adoption is **more concentrated in Free and lower-tier plans**, while **Max and Enterprise users show weaker uptake**, indicating **lower perceived value among high-revenue segments**.
- Users who adopted the feature show **strong engagement**, with **high reports viewed per user and a 92% consumption rate**, confirming that **once used, the feature delivers clear value**.
- **Adopters are more consistently active (higher WAU)** compared to non-adopters, showing a **positive impact on retention and product stickiness**.

### **Recommendations**

- **Increase adoption among high-value segments (Max, Enterprise)** by aligning the feature with their more complex reporting needs
- **Drive behavior shift from manual to automated reporting** through onboarding, prompts, and default scheduling options
- **Leverage strong engagement as a growth lever** by highlighting the value of automated insights in product messaging
- **Target Free users for conversion** by positioning Scheduled Reports as a premium workflow efficiency tool

### **Conclusion**

Scheduled Reports **successfully improved engagement and retention among adopters**, confirming that the feature delivers real user value once adopted.

However, its **overall impact is constrained by moderate adoption and low behavior replacement**, with manual reporting still dominant and weaker uptake among high-value users.

To fully solve the business problem of inconsistent engagement and low stickiness, the focus should shift from **feature performance to adoption expansion and workflow integration**.

### Dashboard

![image.png](attachment:137b27c8-6c96-4e68-8047-f073eaec0a62:image.png)

## **Contact**

- Email: [osazeedogun18@gmail.com](mailto:osazeedogun18@gmail.com) | LinkedIn: www.linkedin.com/in/osaze-edogun | GitHub: https://github.com/osaze32
