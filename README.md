#Stormpath is Joining Okta
We are incredibly excited to announce that [Stormpath is joining forces with Okta](https://stormpath.com/blog/stormpaths-new-path?utm_source=github&utm_medium=readme&utm-campaign=okta-announcement). Please visit [the Migration FAQs](https://stormpath.com/oktaplusstormpath?utm_source=github&utm_medium=readme&utm-campaign=okta-announcement) for a detailed look at what this means for Stormpath users.

We're available to answer all questions at [support@stormpath.com](mailto:support@stormpath.com).


## Spring WebMVC Primefaces JSF Example

This is a basic Spring WebMVC app that shows off [Primefaces](http://primefaces.org/) - a UI Framework built on top of [Java Server Faces](http://www.oracle.com/technetwork/java/javaee/javaserverfaces-139869.html).

### Build

```
mvn clean package
```

### Run

```
mvn jetty:run
```

OR

You can deploy the war file from the `target` folder to your container of choice.

### Exercise

```
http://localhost:8080
```

You'll see the Primefaces Rendered table.
