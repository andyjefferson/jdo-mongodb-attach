jdo-mongodb-attach
==================

Simple test of use of the JDO API with MongoDB database.
This test persists an object, and detaches it. It then updates the detached object. Finally it attaches the object. It tests whether attaching updates the database representation.

To run this, simply type "mvn clean compile test"
