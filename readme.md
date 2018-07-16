# dropwizard-parent-pom
This pom adds the ability to easily build a Dropwizard application as a Docker
image.  The image is automatically configured to expose ports 8080 and 8081 to
the container host so that the web and admin ports can both be used.  In
addition, the arguments to the application command are set to
`server classpath://config.yaml`.  If necessary this can be overridden in a
child pom.

### Releases

#### 1.3.5-1
* Upgraded Dropwizard to 1.3.5
* Upgraded parent POM, `com.mainstreethub:ecs-parent-pom`, to 1.4.0

#### 1.1.4-5
* Upgraded parent POM, `com.mainstreethub:ecs-parent-pom`, to 1.3.6
* Upgraded `com.mainstreethub:java-commons`, to 1.1.4-11

#### 1.1.4-4
* Updating json-log-bundle to 1.1.4-2. Includes remote_user log fields.

#### 1.1.4-3
* Updating java-commons to 1.1.4-4. Includes a fix to handle Datadog metric overrides.

#### 1.1.4-2
* Updating java-commons to 1.1.4-3. Includes a fix to include environment when forwarding metrics to Datadog.

#### 1.1.4-1
* Upgrading to Dropwizard 1.1.4

#### 1.0.9-1
* Upgrading Dropwizard to 1.0.9
* Improved testing to detect missing dependencies

#### 1.0.5-7
* Upgraded parent POM, `com.mainstreethub:ecs-parent-pom`, to 1.3.2

#### 1.0.5-6
* Upgraded parent POM, `com.mainstreethub:ecs-parent-pom`, to 1.3.1

#### 1.0.5-5
* Fixed issue with removed goal from `docker-maven-plugin`

#### 1.0.5-4
* Upgraded parent POM, `com.mainstreethub:ecs-parent-pom`, to 1.3.0

#### 1.0.5-3
* Upgraded to Dropwizard 1.0.5
* Upgraded dropwizard-metrics-datadog-ecs to 0.4.0
* Added environment library, version 0.3.0
* Added time library, version 0.2.0
* Added dropwizard-config-testing library, version 0.1.0
* Added test to verify POM dependencies

#### 1.0.2-4
* Upgraded parent pom to ecs-parent-pom version 1.1.1.
* Added dropwizard-json-log-bundle 1.0.2-0
* Rename log-format Docker label to archetype

#### 1.0.2-3
* Upgraded parent pom to ecs-parent-pom version 1.1.0.