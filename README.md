# Artemis Activemq AT

## A PROJECT UNDER THE ΙΔΕΑ STATEMENT
--------------------------------------

ArtemisActivemqAT is an implementation of the AT Structures for the Artemis Apache ActiveMQ

Steps to execute :

1. (Build Artemis Active MQ in order to produce the Artemis Active MQ artifacts)
2. export ACTIVEMQ_BRANCH_VERSION='version of Artemis Active MQ branch'
3. mvn clean install -Dmaster


Demo Example :
--------------
How to execute for the master branch of https://github.com/apache/activemq-artemis :

1. git clone https://github.com/apache/activemq-artemis.git
2. cd activemq-artemis
3. mvn clean install -DskipTests
4. export ACTIVEMQ_BRANCH_VERSION=2.8.0-SNAPSHOT (version of the master branch)
5. git clone https://github.com/panossot/ArtemisActivemqAT.git
6. cd ArtemisActivemqAT
7. mvn clean install -Dmaster


How to execute with 2.7.0 release of https://github.com/apache/activemq-artemis :

1. git clone https://github.com/apache/activemq-artemis.git -b 2.7.0
2. cd activemq-artemis
3. mvn clean install -DskipTests
4. export ACTIVEMQ_BRANCH_VERSION=2.7.0
5. git clone https://github.com/panossot/ArtemisActivemqAT.git
6. cd ArtemisActivemqAT
7. mvn clean install -Dmaster


How to execute for 2.6.3.jbossorg-x branch of https://github.com/rh-messaging/jboss-activemq-artemis.git :

1. git clone https://github.com/rh-messaging/jboss-activemq-artemis.git -b 2.6.3.jbossorg-x
2. cd jboss-activemq-artemis
3. mvn clean install -DskipTests
4. export ACTIVEMQ_BRANCH_VERSION=2.6.3.jbossorg-001 (version of 2.6.3.jbossorg-x branch)
5. git clone https://github.com/panossot/ArtemisActivemqAT.git
6. cd ArtemisActivemqAT
7. mvn clean install -Dmaster


## License

Code distributed under [ASL 2.0](LICENSE.txt)(licenses of the Active MQ test sources) and [GNU Lesser General Public License Version 2.1](http://www.gnu.org/licenses/lgpl-2.1-standalone.html) (for the repo).
