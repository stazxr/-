keytool -genkey -alias {别名} -keyalg RSA -storetype PKCS12 -keysize 1024 -validity 365 -keystore d:/keystores/suntaoblogcom.jks -storepass {密钥} -dname "CN=(SunTao), OU=(suntaoblogcom), O=(suntaoblogcom), L=(xa), ST=(sx), C=(cn)"

警告（-keypass {密钥}）: PKCS12 密钥库不支持其他存储和密钥口令。正在忽略用户指定的-keypass值。
