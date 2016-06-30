# p2-umlet
Attempt to create p2 repository of the great umlet plugin.

Unable to use systempath until https://github.com/reficio/p2-maven-plugin/issues/102 is resolved.  otherwise, can create local maven repo and just create P2 directly.

Sample usage with an Eclipse Oomph install:
  <setupTask
      xsi:type="setup.p2:P2Task"
      label="Umlet Diagramming Tool">
    <requirement
        name="com.umlet.plugin"/>
    <repository
        url="https://raw.githubusercontent.com/dhartford/p2-umlet/master/repository/"/>
  </setupTask>
  
