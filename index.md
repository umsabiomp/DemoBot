<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHr000002iZul',
				'Demo_Bot',
				'https://ma1704813706587.my.site.com/ESWDemoBot1705501861512',
				{
					scrt2URL: 'https://ma1704813706587.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ma1704813706587.my.site.com/ESWDemoBot1705501861512/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
