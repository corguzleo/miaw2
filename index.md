<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
  </head>
  <body>
    
  </body>
  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DKc000005GKOK',
				'Embedding_Web_2',
				'https://storm-3c5c39553821c0.my.site.com/ESWEmbeddingWeb21740615847202',
				{
					scrt2URL: 'https://storm-3c5c39553821c0.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://storm-3c5c39553821c0.my.site.com/ESWEmbeddingWeb21740615847202/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
