<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DU7000008YH1p',
				'CCTS_Chat_ES',
				'https://k12--uat.sandbox.my.site.com/ESWCCTSChatES1764106855809',
				{
					scrt2URL: 'https://k12--uat.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://k12--uat.sandbox.my.site.com/ESWCCTSChatES1764106855809/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
