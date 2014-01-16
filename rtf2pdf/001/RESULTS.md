# Manipulate RTF and convert to PDF

<table>
  <tr>
    <td><img src="rtf001.rtf-benchmark.pdf-jpg.jpg-200x200.jpg?raw=true" /></td>
    <td>
      <h3>BENCHMARK</h3>
      <p>Manually Creating in Word 2013</p>
    </td>
  </tr>
  <tr>
    <td><img src="rtf001.rtf-path01.pdf-jpg.jpg-200x200.jpg?raw=true" /></td>
    <td>
      <h3>LibreOffice</h3>
      <pre>{
  "engines":{
    "rtf~string":"native:default",
    "rtf->pdf":"libreoffice:default"
  }
}</pre>
    </td>
  </tr>
</table>
