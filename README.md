
### Gerar o archetype maven

mvn archetype:generate -DartifactId=blog -DgroupId=br.com.alura.maven -DinterativeMode=false -DarchetypeArtifactId=maven-archetype-quickstart

### Adicionar o plugin do jetty ao arquivo pom.xml

 <plugin>
	<groupId>org.eclipse.jetty</groupId>
	<artifactId>jetty-maven-plugin</artifactId>
	<version>9.4.31.v20200723</version>
 </plugin>

### Executar o jetty como server no projeto

mvn jetty:run