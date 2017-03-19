# percobaan

<!DOCTYPE person [
	  <!ELEMENT person    (student+)>
	  <!ELEMENT student   (name | jurusan | kelas)>
	  <!ELEMENT name      (#PCDATA)>
	  <!ELEMENT hobbi     (#PCDATA)>
	  <!ELEMENT favorite  (#PCDATA)>
	]>
	<person>
	   <student>
	      <name>Muhamad Rifan</name>
	      <jurusan>Teknik Informatika</jurusan>
	   </student>
	   <student>
	      <name>Rifan Zamaludin</name>
	      <kelas>Teknik Informatika</kelas>
	   </student>
	   <student>
	      <name>Muhamad Rifan Zamaludin</name>
	      <jurusan>Teknik Informatika</jurusan>       <kelas>2B</kelas>
	   </student>
	</person>
