# tron-sdk
提供波场地址创建、TRX、TRC10、TRC20交易本地签名、广播、解析等功能


打包：gradlew jar
额外依赖：
        <dependency>
            <groupId>com.github.ki5fpl.tronj</groupId>
            <artifactId>abi</artifactId>
            <version>0.4.0</version>
        </dependency>
        <dependency>
            <groupId>com.github.ki5fpl.tronj</groupId>
            <artifactId>client</artifactId>
            <version>0.4.0</version>
        </dependency>
mvn仓库配置：
	<profile>
            <repositories>
                <repository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
                    <id>bintray-ki5fpl-tronj</id>
                    <name>bintray</name>
                    <url>https://dl.bintray.com/ki5fpl/tronj</url>
                </repository>
            </repositories>
            <pluginRepositories>
                <pluginRepository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
                    <id>bintray-ki5fpl-tronj</id>
                    <name>bintray-plugins</name>
                    <url>https://dl.bintray.com/ki5fpl/tronj</url>
                </pluginRepository>
            </pluginRepositories>
            <id>bintray</id>
        </profile>
  </profiles>
  
 <activeProfiles>
      <activeProfile>bintray</activeProfile>
 </activeProfiles>