# Jesse discord reporting library

Post the results of backtests to a discord channel using a webhook

Add the following to your strategy:

	from JesseReportDiscord import sendJesseReportToDiscord
	 
		def terminate(self):
			sendJesseReportToDiscord('http://mydiscordgeneratedwebhook')
