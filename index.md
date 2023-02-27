---
layout: default
title: Home
nav_order: 1
description: "Tidal Flow is a Java based Fluent Assertion Library"
permalink: /
---

# A Simple Yet Powerful Assertion Library
{: .fs-9 }

Are you confused by the many assertion libraries and their methods? 
Do you struggle to determine which assertion type to use with String or Number type assertions? <br>
Tidal Flow can help you write intuitive and fluent assertion methods. 
With Tidal Flow, you only need to remember one assertion method to get the job done.
{: .fs-5 .fw-350 }

## Getting started

### Dependencies

Tidal Flow assertion library is built with Java. This is purely an assertion library, not a testing framework. 
It is built using core java and no existing assertion libraries are being used under the hood. 


### To start add the following Maven dependency to your pom.xml file

```xml
        <dependency>
            <groupId>io.github.tidal-code</groupId>
            <artifactId>flow</artifactId>
            <version>1.0.0</version>
        </dependency>
```

{: .pt-4 }
Tidal is hosted with [Maven Central](https://mvnrepository.com/artifact/io.github.tidal-code/flow){:target='_blank'}. For detailed version information, check the 'Versions' page under the 'Detailed Docs' section. 


For projects using Gradle,
```yml
implementation group: 'io.github.tidal-code', name: 'flow', version: '1.0.0'
```

<br>
Please read the [Detailed-Docs]({{ site.url }}/docs/detailed-docs) section to know more about Tidal.Flow

<!-- ### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/tidal-code/Wave#readme). -->


<!-- #### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul> -->

<!-- ### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/pmarsceill/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository. -->
