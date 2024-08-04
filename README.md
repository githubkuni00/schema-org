# Schema Definitions
Referencies From https://schema.org/

## Schema Organization

```json
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "Organization Name",
  "alternateName": "Organization Name",
  "url": "Organization Url",
  "logo": "Organization Logo",
  "sameAs": "Organization Url"
}
```

## Schema Article

```json
{
  "@context": "https://schema.org",
  "@type": "Article",
  "mainEntityOfPage": {
    "@type": "WebPage",
    "@id": "https://206.189.144.78/"
  },
  "headline": "Article Title",
  "description": "Article Description",
  "image": [
    "article image 1",
    "article image 2",
  ],
  "publisher": {
    "@type": "Organization",
    "name": "Organization Name",
    "logo": {
      "@type": "ImageObject",
      "url": "Organization Logo"
    }
  },
  "datePublished": "2021-09-22T11:13:25Z",
  "dateModified": "2021-10-09T20:10:25Z"
}
```

## Schema FAQ

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is SampleService?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "SampleService is a leading provider of innovative solutions that cater to a wide range of customer needs, ensuring high-quality and reliability."
      }
    },
    {
      "@type": "Question",
      "name": "What services are offered by SampleService?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "SampleService offers a variety of services, including consulting, development, and support, each tailored to meet the specific needs of our clients."
      }
    },
    {
      "@type": "Question",
      "name": "Does SampleService offer discounts or promotions?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, SampleService regularly offers discounts and promotions. These include seasonal discounts, referral bonuses, and special offers for loyal customers."
      }
    },
    {
      "@type": "Question",
      "name": "How can I access SampleService's offerings?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "You can access our services via our website, which is optimized for both desktop and mobile use. Simply log in to your account or contact our support team for assistance."
      }
    }
  ]
}
```
## Schema Breadcrumb

```json
{
  "@context": "https://schema.org/",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Home",
      "item": "https://www.samplewebsite.com/"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Category",
      "item": "https://www.samplewebsite.com/category"
    },
    {
      "@type": "ListItem",
      "position": 3,
      "name": "Subcategory",
      "item": "https://www.samplewebsite.com/category/subcategory"
    }
  ]
}
```
## Schema Game

```json
{
  "@context": "https://schema.org",
  "@type": "Game",
  "name": "Mystic Adventure",
  "author": {
    "@type": "Person",
    "name": "Jane Smith"
  },
  "headline": "Mystic Adventure - Embark on a Journey of Mystery and Magic",
  "description": "Mystic Adventure is an immersive fantasy game where players explore enchanted lands, solve ancient puzzles, and uncover hidden treasures.",
  "keywords": [
    "mystic adventure",
    "fantasy game",
    "puzzle",
    "exploration",
    "magic",
    "treasure hunt"
  ],
  "image": "https://www.example.com/images/mystic-adventure-cover.jpg",
  "url": "https://www.example.com/mystic-adventure",
  "publisher": {
    "@type": "Organization",
    "name": "Epic Games Studio"
  },
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.7",
    "bestRating": "5",
    "worstRating": "1",
    "ratingCount": "2500"
  },
  "inLanguage": "en-US"
}
```
