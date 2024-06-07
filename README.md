<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <!-- This represent the class xml element -->
  <xs:element name="class">
   <!-- Because this class element has children it's a complex type -->
   <xs:complexType>
     <!-- Sequence is used to keep the order of the child elements -->
     <xs:sequence>
      <!-- First element will be of type string 
        meaning whatever is inside the tags will be a string
      -->
      <xs:element name="firstname" type="xs:string"/>
      <xs:element name="lastname" type="xs:string"/>
      <xs:element name="age" type="xs:int"/>      
     </xs:sequence>
   </xs:complexType>
  </xs:element>
</xs:schema>


<class>
<student>
<firstname>Graham</firstname>
<lastname>Bell</lastname>
<age>20</age> 
</student>
</class>
