<html>
<body>
                <script type='text/javascript'>
   	  function initEmbeddedMessaging() {
        try {
            embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
            embeddedservice_bootstrap.init(
                '00DbY00000AkJWX',
                'Paraguay_Messaging_Deployment',
                'https://ecic--latamdes.sandbox.my.site.com/ESWParaguayMessagingDep1736921111258',
                {
                    scrt2URL: 'https://ecic--latamdes.sandbox.my.salesforce-scrt.com'
                }
            );
        } catch (err) {
            console.error('Error loading Embedded Messaging: ', err);
        }
    };
    </script>
    <script type='text/javascript' src='https://ecic--            
      latamdes.sandbox.my.site.com/ESWParaguayMessagingDep1736921111258/assets/js/bootstrap.min.js'   
      onload='initEmbeddedMessaging()'></script>

</body>
</html>
