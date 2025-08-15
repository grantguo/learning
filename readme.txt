<omci_type name="Bit" >
  <omci_size value="1" />
  <omci_min value="0" />
  <omci_max value="1" />
  <omci_default value="0" />
  <omci_format value="%d" />
</omci_type>


<omci_type name="HexByte" base="Byte">
  <omci_format value="0x%02x" />
</omci_type>

<omci_enumType name="Boolean" base="Byte">
  <omci_max value="1" />
  <omci_enum>
    <omci_when value="0" string="False" />
    <omci_when value="1" string="True" />
    <omci_default string="True" />
  </omci_enum>
</omci_enumType>

<omci_arrayType name="String4" base="Char">
  <omci_occurence value="4" />
  <omci_format_separator value="" />
</omci_arrayType>
