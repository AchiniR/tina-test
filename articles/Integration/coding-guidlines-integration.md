---
article_heading: Coding Guidelines Integration
article_background_image: "/images/article-cover.png"
article_date: 2020-05-04T18:30:00.000+00:00
article_tags:
- JAVA
- Coding
article_authors:
- author_name: Josue Lopes
  author_image: "/images/theepah.jpg"
  description: Theepah has extensive experience in leading several large-scale digital
    transformation programs for financial services clients in Canada, US & the UK.
    She holds a Bachelor's degree in Computer Science from the University of Waterloo,
    and a Master's degree in Business Administration from the Schulich School of Business,
    York University.
  job_title: Software Engineer
article_card_image: "/images/article-card-img.png"
crm_tag: Article_Integration
crm_lead_source: Coding Guidelines Integration
related_case_studies: true
related_events: true
case_study_widget:
- heading: RCATSONE MODERNIZES KEY SOLUTION USING CLOUD-NATIVE TECHNOLOGY WITH RANDOLI
  short_description: Randoli was engaged to modernize the QoSExecutive solution using
    cloud-native technology with a very aggressive timeline to meet the organizations
    key objectives towards modernizing it's application portfolio to be cloud ready.
  link_to_the_case_study: "/case-studies/case-study-rcatsone-modernization"
  crm_tag: rcatsone_qos
- heading: POSTAL TECHNOLOGY COMPANY MODERNIZES APPLICATIONS USING CLOUD-NATIVE TECHNOLOGY
    WITH REDHAT & RANDOLI
  short_description: In order to handle the year over year growth in transaction volumes
    during the holiday shopping season, the company entrusted Red Hat & Randoli to
    provide thought leadership & software delivery services to help modernize its
    payment gateway
  link_to_the_case_study: "/case-studies/case-study-postal-tech-company-modernization"
  crm_tag: innovapost_cpsa
event_widget:
- heading: Event-Driven Microservices
  short_description: Event-driven Microservices backed by highly available messaging
    infrastructure helps you build robust, resilient & highly scalable applications.
  link_to_the_event: "/events/fy2020-q3-event-driven-architecture-live-event"
  crm_tag: FY2020_Q3_event
  event_date: 2020-09-12T10:00:05.000+00:00
article_category: Integration
featured_article: true
article_short_description: Use Immutable Value Objects With A Defined Eqaulity Test  When
  integrating systems, you would find the need to model a value with more than one
  dimension and share it between classes/functions in your application.

---
### Use Immutable Value Objects With A Defined Eqaulity Test

When integrating systems, you would find the need to model a _value_ with more than one dimension and share it between
classes/functions in your application.

- A date range with start & end date

```java
public class DateRange{
    Date start;
    Date end;
}
```

- A Currency object with value & currency code

```java
public class Currency{
    String code;
    double value;
}
```

A common source of bugs with this approach can be attributed to,

- A value being accidentally updated
- Equality test failing even when the values are the same.

These issues can be avoid by,

- Making the _Value Object_ immutable (no setters or publicly accessible fields)
- Overriding (Ex Java) or Defining (Ex JavaScript) an equals method that makes sense for the _Value Objects_ being compared.

For more informaiton read Martin Fowlers take on it [here](https://martinfowler.com/bliki/ValueObject.html)