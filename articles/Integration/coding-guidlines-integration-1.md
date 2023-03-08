---
article_heading: Coding Guidelines Integration 1
article_background_image: ''
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
article_category: Integration
article_short_description: Multi-fact filtering gives you the power to create comparisons
  that drill down to the most important elements to you, negating the need to swap
  back and forth between multiple filters.

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