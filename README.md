# sciebonoguide-self-engin-tshi
discovery education technologie , technologie engineering
Gmail	tshingombe fiston <tshingombefiston@gmail.com>
sciebono self discovery
postmaster@sci-bono.co.za <postmaster@sci-bono.co.za>	Sun, Apr 21, 2024 at 3:47 PM
To: tshingombefiston@gmail.com
Your message to margeaux.groenewald@sci-bono.co.za couldn't be delivered.
margeaux.groenewald wasn't found at sci-bono.co.za.
tshingombefiston 	Office 365 	margeaux.groenewald
Action Required 		Recipient
				
Unknown To address 		

How to Fix It
The address may be misspelled or may not exist. Try one or more of the following:

    Send the message again following these steps: In Outlook, open this non-delivery report (NDR) and choose Send Again from the Report ribbon. In Outlook on the web, select this NDR, then select the link "To send this message again, click here." Then delete and retype the entire recipient address. If prompted with an Auto-Complete List suggestion don't select it. After typing the complete address, click Send.
    Contact the recipient (by phone, for example) to check that the address is correct.
    The recipient may have set up email forwarding to an incorrect address. Ask them to check that any forwarding they've set up is working correctly.
    Clear the recipient Auto-Complete List in Outlook or Outlook on the web by following the steps in this article: Fix email delivery issues for error code 5.1.1 in Office 365, and then send the message again. Retype the entire recipient address before selecting Send.


Was this helpful? Send feedback to Microsoft.

More Info for Email Admins
Status code 554 5.4.14

Typically this error occurs because the recipient email address is incorrect or doesn't exist at the destination domain. This can usually be fixed by the sender. However, sometimes the issue needs to be fixed by the recipient or the recipient's email admin. If the steps in the How to Fix It section above don't fix the problem, and you're the email admin for the recipient, try one or more of the following:

The email address exists and is correct - Confirm that the recipient address exists, is correct, and is accepting messages.

Synchronize your directories - If you have a hybrid environment and are using directory synchronization make sure the recipient's email address is synced correctly in both Office 365 and in your on-premises directory.

Errant forwarding rule - Check for forwarding rules that aren't behaving as expected. A forwarding rule can be configured by an admin via mail flow rules or mailbox forwarding address settings, or by the recipient via the Inbox Rules feature.

Mail flow settings and MX records are not correct - Misconfigured mail flow settings or MX records can cause this error. Check your Office 365 mail flow settings to make sure your domain and any mail flow connectors are set up correctly. Also, work with your domain registrar to make sure the MX records for your domain are configured correctly.

Mail loop detected - This error also indicates that the receiving organization's email settings are misconfigured, creating a mail loop when a message is sent to an address that isn't found in their directory. This usually won't disrupt mail flow for recipients that actually exist, but the recipient's email admin should fix the misconfiguration to reduce the chance of any other mail flow issues. A common cause for this loop is that the recipient's domain is configured as "Internal Relay" when it should be "Authoritative." Another common cause for the loop is that both the sender and recipient are part of the same organization, but the sender's mailbox is hosted by Office 365, while the recipient's mailbox is hosted on-premises, and an outbound connector from Office 365 to the on-premises email servers is missing or misconfigured. To fix this, the recipient's email admin should create a correctly configured outbound connector in Office 365 to route the message to the on-premises mailbox.

For more information and tips to fix this problem, see Fix email delivery issues for error code 5.4.14 in Office 365.

Original Message Details
Created Date: 	4/21/2024 1:47:16 PM
Sender Address: 	tshingombefiston@gmail.com
Recipient Address: 	margeaux.groenewald@sci-bono.co.za
Subject: 	Re: sciebono self discovery

Error Details
Error: 	554 5.4.14 Hop count exceeded - possible mail loop ATTR34 [DU2PEPF00028D13.eurprd03.prod.outlook.com 2024-04-21T13:47:53.142Z 08DC618C59ADCC5C]
Message rejected by: 	DU2PEPF00028D13.mail.protection.outlook.com

Notification Details
Sent by: 	AS8P193MB2064.EURP193.PROD.OUTLOOK.COM

Message Hops
HOP 	TIME (UTC) 	FROM 	TO 	WITH 	RELAY TIME
1 	4/21/2024
1:47:35 PM 		mail-lj1-f179.google.com 	SMTP 	19 sec
2 	4/21/2024
1:47:35 PM 	mail-lj1-f179.google.com 	AMS0EPF000001AC.mail.protection.outlook.com 	Microsoft SMTP Server (version=TLS1_3, cipher=TLS_AES_256_GCM_SHA384) 	*
3 	4/21/2024
1:47:35 PM 	AMS0EPF000001AC.eurprd05.prod.outlook.com 	AM6P195CA0007.outlook.office365.com 	Microsoft SMTP Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) 	*
4 	4/21/2024
1:47:35 PM 	AM6P195CA0007.EURP195.PROD.OUTLOOK.COM 	AM8P193MB1217.EURP193.PROD.OUTLOOK.COM 	Microsoft SMTP Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) 	*
5 	4/21/2024
1:47:41 PM 	EUR03-AM7-obe.outbound.protection.outlook.com 	DU2PEPF00028D01.mail.protection.outlook.com 	Microsoft SMTP Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) 	6 sec
6 	4/21/2024
1:47:41 PM 	DU2PEPF00028D01.eurprd03.prod.outlook.com 	DB7PR02CA0020.outlook.office365.com 	Microsoft SMTP Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) 	*
7 	4/21/2024
1:47:41 PM 	DB7PR02CA0020.eurprd02.prod.outlook.com 	AM9P193MB0856.EURP193.PROD.OUTLOOK.COM 	Microsoft SMTP Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) 	*
8 	4/21/2024
1:47:46 PM 	EUR05-DB8-obe.outbound.protection.outlook.com 	DU2PEPF00028D0D.mail.protection.outlook.com 	Microsoft SMTP Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) 	5 sec
9 	4/21/2024
1:47:46 PM 	DU2PEPF00028D0D.eurprd03.prod.outlook.com 	DUZPR01CA0193.outlook.office365.com 	Microsoft SMTP Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) 	*
10 	4/21/2024
1:47:46 PM 	DUZPR01CA0193.eurprd01.prod.exchangelabs.com 	AS8P193MB2064.EURP193.PROD.OUTLOOK.COM 	Microsoft SMTP Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) 	*

Original Message Headers

ARC-Seal: i=5; a=rsa-sha256; s=arcselector9901; d=microsoft.com; cv=pass;
 b=IqRBIQBMoyKf/I6nGj0Luw/D60tVGzaZMqKkdGWFundfpgR8PcDtMomyrY7x0Yn2y9YlucCj5wnRvnnyKqpPhNX+/pNJctH4MJolnrWYRe6XIUbLWmTYPsLbbzIm4boWAGMYFKwCNJA1V3oIGLSVxRHxa23gBSe3ajNCucR/WOOtxcchM8YCyNF2mnkkZRggzsqQ/B0K9Euk13IJim2eJdBM/ITv5lyJtoTJ1GtBKf/xZLskcrxiIkiRgFPyE1RVIrH6HMw7N+XvgKBk2vAapr5G2fuqUGOrKImUJL9XIAHO3vm1hAyNk3yZ0OhY5c88Uk7n9GIVgnvm6iVdunLeEw==
ARC-Message-Signature: i=5; a=rsa-sha256; c=relaxed/relaxed; d=microsoft.com;
 s=arcselector9901;
 h=From:Date:Subject:Message-ID:Content-Type:MIME-Version:X-MS-Exchange-AntiSpam-MessageData-ChunkCount:X-MS-Exchange-AntiSpam-MessageData-0:X-MS-Exchange-AntiSpam-MessageData-1;
 bh=DWDR2iwzSvw3ZfkZvsRLibSr00NeZ0nRvnJPWIm5qDg=;
 b=iXJxGtzR/OSWAbUqw3uP0fp7tT75Ktszu9/DJhc9bCL8APGsGcwVNF/X8GY+Mzyo5zg9DJ000V9zmma/rA5m5rqnlHbSAMZ0GK5axvhDuOB+RwsQ+2zOCDD1Ivl9nMNPFT7hDyoGE5CXovn7wKHKbYe1PquN8WhZpU+OGTOQqP5X4CwhD4BHJNNWX6gaNl3P8DjOS6V5gr5mOmvsOtir1zMm+uOZE13t5X9tXeKMPSw1DAf8besMwtJKs0iC2MRX3VQgAnlmb+Q/bHRfRZbQ6Va5phrKZbXjTyDugJ+s08pFPOdluffRLzW4X6a0eF7VwrfiaiXd21Zk4/2YlrEhFw==
ARC-Authentication-Results: i=5; mx.microsoft.com 1; spf=softfail (sender ip
 is 104.47.17.104) smtp.rcpttodomain=scibonocoza.mail.onmicrosoft.com
 smtp.mailfrom=gmail.com; dmarc=pass (p=none sp=quarantine pct=100)
 action=none header.from=gmail.com; dkim=pass (signature was verified)
 header.d=gmail.com; arc=pass (0 oda=1 ltdi=1
 spf=[1,1,smtp.mailfrom=gmail.com] dkim=[1,3,header.d=gmail.com]
 dmarc=[1,3,header.from=gmail.com])
ARC-Seal: i=4; a=rsa-sha256; s=arcselector9901; d=microsoft.com; cv=pass;
 b=AaQUpR1dG714w9PrRbuskR+9q975IBSXkMm+7gP7unNXM+cgSc0+ihgh5VkGKiWLFc64UtJ5+jYg3JPnuwnAK9diqRlfNvW1EBMR8PolecqjAfNsfTUpSVpFVDHix9YLL0+UM4g5zYoQs3U5fGFBgU1qg0+Bw4lFWSMsXK/TZ/Ks3+4MR0/4DM5XbBE4YpB37LEBq7QLeGNtAL9Z1t/uoztFeybT+AI5nOskBwp804QXd0pH6/FE3BfGEKFLge7cJ+AUVjSfPp1N7dZeOOiCyDAxmjgEeZWtfqenIUJ7jK/quSbZH51xrU5k/dONbDc2sdAygDz7eozg8u50OAW+fA==
ARC-Message-Signature: i=4; a=rsa-sha256; c=relaxed/relaxed; d=microsoft.com;
 s=arcselector9901;
 h=From:Date:Subject:Message-ID:Content-Type:MIME-Version:X-MS-Exchange-AntiSpam-MessageData-ChunkCount:X-MS-Exchange-AntiSpam-MessageData-0:X-MS-Exchange-AntiSpam-MessageData-1;
 bh=DWDR2iwzSvw3ZfkZvsRLibSr00NeZ0nRvnJPWIm5qDg=;
 b=VP8iKl32NN6F/gHerg+zfIPWKBGaYzeUW3fDAaMN8RQQrZpb4sZhhkkF3abhveiUWGD2AUBD5FmOYBEq4ocDhXKekCDefAPHdJ6rojYekc82gj7lXq2jyIS73pKSUfyw5dDbc5ePE8zCMm7v9KMhIbLzgLjRSX3lWiXykhOILTI6KjhjXa8AUnpgb5r6Gdsf3dOJmIxp3A4Jrl9sRQlCkhJvr6pheVFntUGH2ripE5tCnl6s1AGgAyCZnWLEMT89amPUcKQbu7tgDqVHl2FmoAKglUdFMmQRiN+Nn5agDCMTg+I6stxvbGBIv0U3RxxzZJXFoxKC6tSnsgE6Rt5G1Q==
ARC-Authentication-Results: i=4; mx.microsoft.com 1; spf=softfail (sender ip
 is 104.47.17.104) smtp.rcpttodomain=scibonocoza.mail.onmicrosoft.com
 smtp.mailfrom=gmail.com; dmarc=pass (p=none sp=quarantine pct=100)
 action=none header.from=gmail.com; dkim=pass (signature was verified)
 header.d=gmail.com; arc=pass (0 oda=1 ltdi=1
 spf=[1,1,smtp.mailfrom=gmail.com] dkim=[1,3,header.d=gmail.com]
 dmarc=[1,3,header.from=gmail.com])
Received: from DUZPR01CA0193.eurprd01.prod.exchangelabs.com
 (2603:10a6:10:4b6::14) by AS8P193MB2064.EURP193.PROD.OUTLOOK.COM
 (2603:10a6:20b:44b::10) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.7472.44; Sun, 21 Apr
 2024 13:47:46 +0000
Received: from DU2PEPF00028D0D.eurprd03.prod.outlook.com
 (2603:10a6:10:4b6:cafe::c3) by DUZPR01CA0193.outlook.office365.com
 (2603:10a6:10:4b6::14) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.7495.33 via Frontend
 Transport; Sun, 21 Apr 2024 13:47:46 +0000
Authentication-Results: spf=softfail (sender IP is 104.47.17.104)
 smtp.mailfrom=gmail.com; dkim=pass (signature was verified)
 header.d=gmail.com;dmarc=pass action=none header.from=gmail.com;compauth=pass
 reason=100
Received-SPF: SoftFail (protection.outlook.com: domain of transitioning
 gmail.com discourages use of 104.47.17.104 as permitted sender)
Received: from EUR05-DB8-obe.outbound.protection.outlook.com (104.47.17.104)
 by DU2PEPF00028D0D.mail.protection.outlook.com (10.167.242.21) with Microsoft
 SMTP Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id
 15.20.7519.19 via Frontend Transport; Sun, 21 Apr 2024 13:47:46 +0000
ARC-Seal: i=3; a=rsa-sha256; s=arcselector9901; d=microsoft.com; cv=pass;
 b=XG0lTEMRplS5nG49zGzt6lFLoXSSv5dJf6SWpPVUi3RNM5AV2KUQootDp52eX7nQSVcExOeBhQ/KKyqTZCmRTDZme+ZVvdGemCUrBKQrRtQ3uJRI52aLVkBj/XWJiC4kAwl6eDVvxYXHVCabk2VBzlNGyGnD0VOQZYdJwNvGfeNKcv5EvwVEaZmh5LhSLvlYhflgvoI2VCZN3x0RYXH0mLBCCjE+/i5rPExHaaBqc6QR5gtcrlmv4oMeu3e8yP0wCLNQ7doMNd3fP99OBj4xaLgde2kt27eZxGVYAmoyzrklQMko1cp0QjT9peFRhsIjjIi4aJOAXi2ndk1R8pw7yQ==
ARC-Message-Signature: i=3; a=rsa-sha256; c=relaxed/relaxed; d=microsoft.com;
 s=arcselector9901;
 h=From:Date:Subject:Message-ID:Content-Type:MIME-Version:X-MS-Exchange-AntiSpam-MessageData-ChunkCount:X-MS-Exchange-AntiSpam-MessageData-0:X-MS-Exchange-AntiSpam-MessageData-1;
 bh=DWDR2iwzSvw3ZfkZvsRLibSr00NeZ0nRvnJPWIm5qDg=;
 b=HoSk5bCquRpqys4Dnpbo7y2/JVEJKCqDXemHmoKGQQoPAotyWYiMAck4zAgf/I2h5U6wKTFWNGJKhGoRgSKoyuXyxrke7rfUy0FPiPq0z8J+bSxN5W5yVyzaEd52QovVRxJ5HjdJ1V+d0odqbRGMwKF7lF/2HrrxXp1sexz5KeZuDg7rN3SVOvPaj6y24/yjonEEY2U7rUPv2I2Hz9iWXu6G9Mxn2qCPO811NEnAnahvCJUrFkeBs5SbPiHe+mV0lZKdNWGpEb7L2xuRUirlBnMbeweT/V9MthV5XViAzWfyPQdzhuOsP+RRt4Bvy24JeB9ujViLFtllarOrmH13Qw==
ARC-Authentication-Results: i=3; mx.microsoft.com 1; spf=softfail (sender ip
 is 104.47.51.232) smtp.rcpttodomain=scibonocoza.mail.onmicrosoft.com
 smtp.mailfrom=gmail.com; dmarc=pass (p=none sp=quarantine pct=100)
 action=none header.from=gmail.com; dkim=pass (signature was verified)
 header.d=gmail.com; arc=pass (0 oda=1 ltdi=1
 spf=[1,1,smtp.mailfrom=gmail.com] dkim=[1,1,header.d=gmail.com]
 dmarc=[1,1,header.from=gmail.com])
ARC-Seal: i=2; a=rsa-sha256; s=arcselector9901; d=microsoft.com; cv=pass;
 b=Ul9heYyayej3NzNg/zuOam4I8VzPjamhfFlizsgQSQzgDNOPy+nem9L4QwJAGf6O3xW6iO/2WbMDey2eRJQFwT54bPzCTiOjV9SwrZOq9XepR6h+jC/HxQw4qCfr03cXsJcG0i6ogMhtowSkGP39tyoNAqsGXXlkPdBpxeyXf7lSB01PIT1evkXgHYhLM71K9VP68/4bPXOCHsMqLzeFWcRRawN7/8mHPXI9bms8B+hTDhYSFPD+SIlnR/5TvJUWi544mpwrEfD3pzCaZl868gFP0lgOriPSSB0fq+DBRBKp9derA0bqsHOOH+WVkNnrBFq+1m9EULISSFa8D19OCQ==
ARC-Message-Signature: i=2; a=rsa-sha256; c=relaxed/relaxed; d=microsoft.com;
 s=arcselector9901;
 h=From:Date:Subject:Message-ID:Content-Type:MIME-Version:X-MS-Exchange-AntiSpam-MessageData-ChunkCount:X-MS-Exchange-AntiSpam-MessageData-0:X-MS-Exchange-AntiSpam-MessageData-1;
 bh=DWDR2iwzSvw3ZfkZvsRLibSr00NeZ0nRvnJPWIm5qDg=;
 b=aaIqBFMUUhLeLuZdKOMcSLiJ6qh20N5Jac8Uy+etFuGs83Ach4kEVxV3OCVOWxKGSVGtplKWWcLPWscuHa/n5elyJ4DdXoR8AOprl00wXwvgeNFXac+HlY/PKExPwa0xbvd1bGgWpEtTwM26Afo5OokldJa/25Nenf7VeH+9vIzM7TIjGvntxIiZQkAO9tDOKekDr0I3+/TZKfNFlnBSj0c2yeUCHybPZ1WgSnNGPqsK4pch9C7sF/V10wJ34EQ5W5/y28pXusvoDBr/E1tb5Vo5NHrt57F69A14Rhk0WPLmsuPZaaWBIie+fs6CSlBKAW0A63W3tGb2AIuboDJZeQ==
ARC-Authentication-Results: i=2; mx.microsoft.com 1; spf=softfail (sender ip
 is 104.47.51.232) smtp.rcpttodomain=scibonocoza.mail.onmicrosoft.com
 smtp.mailfrom=gmail.com; dmarc=pass (p=none sp=quarantine pct=100)
 action=none header.from=gmail.com; dkim=pass (signature was verified)
 header.d=gmail.com; arc=pass (0 oda=1 ltdi=1
 spf=[1,1,smtp.mailfrom=gmail.com] dkim=[1,1,header.d=gmail.com]
 dmarc=[1,1,header.from=gmail.com])
Received: from DB7PR02CA0020.eurprd02.prod.outlook.com (2603:10a6:10:52::33)
 by AM9P193MB0856.EURP193.PROD.OUTLOOK.COM (2603:10a6:20b:1fc::8) with
 Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.7472.44; Sun, 21 Apr
 2024 13:47:41 +0000
Received: from DU2PEPF00028D01.eurprd03.prod.outlook.com
 (2603:10a6:10:52:cafe::5a) by DB7PR02CA0020.outlook.office365.com
 (2603:10a6:10:52::33) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.7495.33 via Frontend
 Transport; Sun, 21 Apr 2024 13:47:41 +0000
Authentication-Results-Original: spf=softfail (sender IP is 104.47.51.232)
 smtp.mailfrom=gmail.com; dkim=pass (signature was verified)
 header.d=gmail.com;dmarc=pass action=none header.from=gmail.com;compauth=pass
 reason=100
Received-SPF: SoftFail (protection.outlook.com: domain of transitioning
 gmail.com discourages use of 104.47.51.232 as permitted sender)
Received: from EUR03-AM7-obe.outbound.protection.outlook.com (104.47.51.232)
 by DU2PEPF00028D01.mail.protection.outlook.com (10.167.242.185) with
 Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.7519.19 via Frontend
 Transport; Sun, 21 Apr 2024 13:47:41 +0000
ARC-Seal: i=1; a=rsa-sha256; s=arcselector9901; d=microsoft.com; cv=none;
 b=G+GW3ptWaFXo3WDu/NYhf+cHJk95c1yQ/rzPAElBv3POeNDCmHUJVHbBGfLsM0hmfKVkMjHF1sQrPAQBEXZ3fwyon9AXWOPvz/FZkNzYGH6gboSjE80eKZ2PmvEeNqJ/89vC6zjicfwzrxN+Ixvc0MrwL3QkCnGuWAdfUZ/Xua4v0VYjpiyMlwtVnwcwZAxnhUm3wA1Gmjr8A0r06Gmcq+F05Wd+DmgoGwVDYEsSo9vGuTo6C27vY9GJ3+BWhLSbMEISvgHkimLrbtrUaFXsShgCGKah/vwvPHueBDhgkndvU+AQFs8dcFZWxYiI97tm4lddxh1Q6M/oTBMsmALgng==
ARC-Message-Signature: i=1; a=rsa-sha256; c=relaxed/relaxed; d=microsoft.com;
 s=arcselector9901;
 h=From:Date:Subject:Message-ID:Content-Type:MIME-Version:X-MS-Exchange-AntiSpam-MessageData-ChunkCount:X-MS-Exchange-AntiSpam-MessageData-0:X-MS-Exchange-AntiSpam-MessageData-1;
 bh=DWDR2iwzSvw3ZfkZvsRLibSr00NeZ0nRvnJPWIm5qDg=;
 b=ZeyYBwoQg2r7PozcaA2aLVDbwYGKvsisN2EBoAEUDlwbBLUUxANX5IpfxhlRxRj4gPS/nmKBQ5gYJ9IvLQ94x/IFypoRrOMCSpEQ6Ow1Cc+ry5RpftAZFPqw/NkBjQlE9WQdwEyaKRe1PZfFjNAywpj1s1AbUWgy0UYfw3RpHD5OVhphTZGBvAu6gEqeeW5MCJTNGwdFQdjtzsqyxDenBWP6d2p5nkIIvL1hoGlLykWw8il2PYaWhtRGq/Bu+AgNlSHmcp747AvMCxeKtwNkOl6hnVYfg5ymKZSSxldF8g80hpu0jn2XK8AFIGDJYZVGx6XL01CPlH4/OwcGSo4tcw==
ARC-Authentication-Results: i=1; mx.microsoft.com 1; spf=pass (sender ip is
 209.85.208.179) smtp.rcpttodomain=sci-bono.co.za smtp.mailfrom=gmail.com;
 dmarc=pass (p=none sp=quarantine pct=100) action=none header.from=gmail.com;
 dkim=pass (signature was verified) header.d=gmail.com; arc=none (0)
Received: from AM6P195CA0007.EURP195.PROD.OUTLOOK.COM (2603:10a6:209:81::20)
 by AM8P193MB1217.EURP193.PROD.OUTLOOK.COM (2603:10a6:20b:317::21) with
 Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.7472.44; Sun, 21 Apr
 2024 13:47:35 +0000
Received: from AMS0EPF000001AC.eurprd05.prod.outlook.com
 (2603:10a6:209:81:cafe::fc) by AM6P195CA0007.outlook.office365.com
 (2603:10a6:209:81::20) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.7495.30 via Frontend
 Transport; Sun, 21 Apr 2024 13:47:35 +0000
Authentication-Results-Original: spf=pass (sender IP is 209.85.208.179)
 smtp.mailfrom=gmail.com; dkim=pass (signature was verified)
 header.d=gmail.com;dmarc=pass action=none header.from=gmail.com;compauth=pass
 reason=100
Received-SPF: Pass (protection.outlook.com: domain of gmail.com designates
 209.85.208.179 as permitted sender) receiver=protection.outlook.com;
 client-ip=209.85.208.179; helo=mail-lj1-f179.google.com; pr=C
Received: from mail-lj1-f179.google.com (209.85.208.179) by
 AMS0EPF000001AC.mail.protection.outlook.com (10.167.16.152) with Microsoft
 SMTP Server (version=TLS1_3, cipher=TLS_AES_256_GCM_SHA384) id 15.20.7519.19
 via Frontend Transport; Sun, 21 Apr 2024 13:47:35 +0000
Received: by mail-lj1-f179.google.com with SMTP id 38308e7fff4ca-2d8a24f8a3cso43057881fa.1
        for <margeaux.groenewald@sci-bono.co.za>; Sun, 21 Apr 2024 06:47:35 -0700 (PDT)
DKIM-Signature: v=1; a=rsa-sha256; c=relaxed/relaxed;
        d=gmail.com; s=20230601; t=1713707254; x=1714312054; darn=sci-bono.co.za;
        h=to:subject:message-id:date:from:in-reply-to:references:mime-version
         :from:to:cc:subject:date:message-id:reply-to;
        bh=DWDR2iwzSvw3ZfkZvsRLibSr00NeZ0nRvnJPWIm5qDg=;
        b=hVYwFVaEJXZ00tfwFvepc2mHutAjZEBeLyltxCdXUf1BL1GxI39uv/L+1PubFoYBaA
         VLWJu6MRNJ8Liay4m5ap0xaxzJmdsP6LnF8X+3+6qvHSWpbfpCge/TlLP2RvhdGhHgNf
         1qe1gJOKJ6tCiIlxnp2as3d1M/ufBboq0wsBqo7ZEp0uc8Efzp8YUDT0v4M7KAQoipE5
         od3kPvPamnBJ1RD8cCZhj/SEvcTtGJPoR4ulR1pqAo3wk1PDnkJKAMjfH/+YHVe7bNSQ
         cUoFJa8Cc+PU+3c0HeOf5nx9XSITVx7K2vO10VNB/D6vIwRR0wq9lH0UEsCNceO5ja+N
         XNRQ==
X-Google-DKIM-Signature: v=1; a=rsa-sha256; c=relaxed/relaxed;
        d=1e100.net; s=20230601; t=1713707254; x=1714312054;
        h=to:subject:message-id:date:from:in-reply-to:references:mime-version
         :x-gm-message-state:from:to:cc:subject:date:message-id:reply-to;
        bh=DWDR2iwzSvw3ZfkZvsRLibSr00NeZ0nRvnJPWIm5qDg=;
        b=HNFJ1SJIzNVbt2Q2yrnsmN/letaErsHY/025+GInT0VsuOyJpY8gyStI1ezeJSA5Vb
         YyrH29ZACi3EcHAybliTocoCmXNv5r+opQkiDiIoqjQ/2VjPwkk0SIOb6m/oIUEphXtu
         ff+ojf1uhVpU2Py73RVK+8wVmWCbn9cVan4XtG55Z3JLeX2633bYwgtt1dIc+Ljndy1R
         m/6xV1ayUzpqLGCcv73OrYRgHmb0SJzpZkxxk03NExmwHelIPzGJerJfrsrh6ldPONUx
         NdXcoo5XdRHb+xihqZ/vut60GJMboOrQTiPq1DO/qAdH9YcjCGtkgvbvjiRBiIxY2cSw
         VuAA==
X-Forwarded-Encrypted: i=1; AJvYcCXsD7ZY7hCPbhwrD0okAYVA5vU7k7uMh+BNuWOrPaxA6ircL8dpyC6m45HAyEcAAb6xwGJQmcycVFoISZhzU+8L11v7D3KaxhO8pRBa9XJ+PMv1
X-Gm-Message-State: AOJu0YyScLYzSc3P0cHKIT7zFVmM+fsK0g338bX1BZPsR1jhB/DL1/81
	DWdlbo0aXAk82gWa1j5Cr4xv7xpTmcCOEe5UCkGgzIr9Wc+CkQgYXm+ioczVCGmzE6+FtGBFw7Y
	v3WN0m+LtDKtS+dFKzgB8S/F0dBvD0A==
X-Google-Smtp-Source: AGHT+IEIkHAB9ZeeVYEzAMQzQEKmeN6/IkoXjxHtbWrkh30zch3AMyFmv5cX4P6S/X9SewWtltK6+3TXwMSfTqcbd/A=
X-Received: by 2002:a05:6512:3d2a:b0:51b:14d9:9c12 with SMTP id
 d42-20020a0565123d2a00b0051b14d99c12mr1226910lfv.30.1713707251901; Sun, 21
 Apr 2024 06:47:31 -0700 (PDT)
MIME-Version: 1.0
References: <CABd78RVfyuz9DuXZ=FN9pRiAGhDW30GnrghqeHtZGx9Pt8O0Mw@mail.gmail.com>
 <CABd78RXG3kxy1Da0B68bAXSxmvzN__cj_DequFuSCuvGFGpeDw@mail.gmail.com> <CABd78RVfb9e9OcQmu8wSeohb3MN03dD1ZV7DBY8RNGGuHKR80A@mail.gmail.com>
In-Reply-To: <CABd78RVfb9e9OcQmu8wSeohb3MN03dD1ZV7DBY8RNGGuHKR80A@mail.gmail.com>
From: tshingombe fiston <tshingombefiston@gmail.com>
Date: Sun, 21 Apr 2024 15:47:16 +0200
Message-ID: <CABd78RXkBa03PRhyRardgNzwn2=WC_aeEkFZqH3aN4HeC8=f7w@mail.gmail.com>
Subject: Re: sciebono self discovery
To: tshigombekb@gmail.com, tshingombe fiston <tshingombefiston@gmail.com>, 
	tshingombe tshitadi <tshitaditshingombe@gmail.com>, tahitaditshingombe@gmail.com, 
	tshitaditshingombe@yahoo.fr, TSHINGOMBEKB TSHITADI <TSHINGOMBEKB@gmail.com>, info@sciebono.coza, 
	margeaux.groenewald@sci-bono.co.za
Content-Type: multipart/mixed; boundary="000000000000ffe04c06169b8f43"
Return-Path: tshingombefiston@gmail.com
X-EOPAttributedMessage: 2
X-EOPTenantAttributedMessage: ac15f455-2df6-42bd-924f-102f0ec7acfb:2
X-MS-TrafficTypeDiagnostic:
	AMS0EPF000001AC:EE_|AM8P193MB1217:EE_|DU2PEPF00028D01:EE_|AM9P193MB0856:EE_|DU2PEPF00028D0D:EE_|AS8P193MB2064:EE_
X-MS-Office365-Filtering-Correlation-Id: cc51f39d-479c-40aa-44be-08dc6209a045
X-LD-Processed: ac15f455-2df6-42bd-924f-102f0ec7acfb,ExtAddr,ExtAddr,ExtAddr
X-Microsoft-Antispam-Untrusted: BCL:0;
X-Microsoft-Antispam-Message-Info-Original: =?us-ascii?Q?1bt+QNDThJXAXFx5KH2dqF1A8K3XDIxgHVBJRYSotdCnj2fOrkLS694WDjaT?=
 =?us-ascii?Q?huzrArorz13cslMT0Z+nZxMk7Z/vtoz4ivlFZCiDi5KoQwnjZrztNCL7PNbF?=
 =?us-ascii?Q?OBS9WqTMYhJxUtrk/YDdEZgdQwas1oaUpinNfaJB85qVbpZfh03egPto2RUx?=
 =?us-ascii?Q?phmh7yzQ3x6XjMRTHwBAE2sXjcspEwR6ykDltuYEb2vQ+FW98/VTRnsDnrgV?=
 =?us-ascii?Q?7F1Ws6+n2bWYXHKy4rC7CvWLIdipo7ExN0803fzJgrFe7uAOTri1s2Y/VAeE?=
 =?us-ascii?Q?F1TNqXkW92ST6m8TnP8HJO7SUjIn2h6HOrZEYwZzgoqqIBK74N14ZYXRuxM5?=
 =?us-ascii?Q?Q9I7hxflSZyLmzM5TGHEYw3sjk/d/8uzPjJkNSuJclLdzhhHocZPypQrS0fc?=
 =?us-ascii?Q?hlXZegRd1aXV0T5mB+4Ig/qyiftdZ0FnD2a374j2Kq4gnFx0lYdCZcUVtiEe?=
 =?us-ascii?Q?G1wWOQzr3/q9uzKT/+eJdjeIKm02PbhqPtZHRbS2N64jcGheYeIFOFZI1zCm?=
 =?us-ascii?Q?iHeRIaLEQDj4k2iiULQxjcV2CIvp4Q3un8Ez/rJB570m9z+SJdex4/w7xMAR?=
 =?us-ascii?Q?PtdkFxknPQwGsYlVJwy1iHs6iHIOYLLz79R6eWsUduMUBfp2ilQmwtCSPRew?=
 =?us-ascii?Q?PNvdNNX2R1Uv7BPXtKY9tLLT+/lh2Jfjvg26fdfbomILsP7lLw9C9LDHav/F?=
 =?us-ascii?Q?ktF8RvczwUP4T9KlupuPn+mIppBJvSMzHzS9vyfF7TIvjWELJpzPRVPiDf/U?=
 =?us-ascii?Q?GFnc9AdthvOqiKh+R9Zz/xRon3mtGJiCanhvSkclYZVQOjmt3hcxB/zivc6O?=
 =?us-ascii?Q?1uYEcIcs6MaytP4Modp6EsiNIZuHlQyuV/4RwUsYgwsSu8ndhOKxDXNNH4Uo?=
 =?us-ascii?Q?9WyEEIMQCh/hOnQA0P83t/9IlUsRTCK7AIHucam9QlMAVzM2W2EV7clrpNVD?=
 =?us-ascii?Q?YpM4M26LQ6vQBDhUZlcBddEZxrOO4HF6liHl0cIB+QO8x49Rh4stJmQpcxGt?=
 =?us-ascii?Q?+d62MaI1H9uBop8mnRHCw+FGF1gP/BNRJFOuM+pJKmYsDsKtSMqE6LnADIqf?=
 =?us-ascii?Q?4JDuabKj+RLLcm8q2Y1HD4E8UICyI3t3NXRcVR+oMriCls8iV035pvDNKc3i?=
 =?us-ascii?Q?XflfXEHgWyQgQYZrK3W1jTx8QqQfbSA9g3Q7lH9iAZZT9TP2x+7WeEEfzut8?=
 =?us-ascii?Q?WCGEDKz/9TusDdR6CbJd9sBzUR0iNYzZej6DmKglfQxyXP8qzS8CH8XMRsdV?=
 =?us-ascii?Q?GT4YAHe3QPvUXsXOOuk8mM8hokUMCLFsJC+/uSJsah7thy1OhYLT3bkz2+3d?=
 =?us-ascii?Q?CLpfAW3atJ1BM8F7hbRKfbrlwe2gjIK8bgROJ8FulBXV9Lv1HUGN0kHfJPZC?=
 =?us-ascii?Q?B6xRGn2Rx1lszDD/VdW7cpZgFuzW8XeQD+o6oe2W54GLuZY2fOzUUkEr3V6L?=
 =?us-ascii?Q?Qf2ub6ATHlPmSTa+MEYzK4/Lo1zKWGl49Db5uuiDmRQLYtZhU7DUpuy60H1z?=
 =?us-ascii?Q?smEwUsxc3ytLEMex3/p7xLGRHIk7/0jiCBg/kQcHKJVK40SZgCTHsJh6bk7Y?=
 =?us-ascii?Q?IFEUMBH+6AAnqLHE/oE+2PhylZw9JXO0m1+S9PBy0bRDZV6vPB6FjIn7StaX?=
 =?us-ascii?Q?2tsqKZjUZkwTpJ4wLkmLi0w5aDFWui+Y4+myHPktUFCYCwSgVMD19CHqSA1r?=
 =?us-ascii?Q?0nhz8W+QT1awjrUWLILgDqoV6fVzK0OOhxEwMvLLotk8S4quF2VCA11n31Ec?=
 =?us-ascii?Q?UL/szVFY+RFx3pPY1uLBu6nseB5GSB3eEjT5pr3iEnn4GsTSwq/J7O7TrG/O?=
 =?us-ascii?Q?ZJmsljLPBXo2qvWSSyPdHd/nO5IfRSbRGB/Zr9NphH+M+FihABTHL7xWAXXJ?=
 =?us-ascii?Q?CgUmZ0uMx7vS6mze2PULX+X1FPiwZbRcPGa+3NTMbfyN1166oovFFsfgJm5R?=
 =?us-ascii?Q?mDKc0IdbqpnTvvzryeNdT0yNRuRmElhFSSLoemUnuzwZ7cALdfsfHavVOVv8?=
 =?us-ascii?Q?aPx8?=
X-Forefront-Antispam-Report-Untrusted: CIP:209.85.208.179;CTRY:US;LANG:en;SCL:1;SRV:;IPV:NLI;SFV:NSPM;H:mail-lj1-f179.google.com;PTR:mail-lj1-f179.google.com;CAT:NONE;SFS:(13230031)(7093399003);DIR:INB;
X-ExternalRecipientOutboundConnectors: ac15f455-2df6-42bd-924f-102f0ec7acfb
X-MS-Exchange-Transport-CrossTenantHeadersStamped: AM8P193MB1217
X-MS-Exchange-Transport-CrossTenantHeadersStripped: DU2PEPF00028D01.eurprd03.prod.outlook.com
X-MS-Exchange-Transport-CrossTenantHeadersPromoted: DU2PEPF00028D01.eurprd03.prod.outlook.com
X-MS-Office365-Filtering-Correlation-Id-Prvs: 0b8f6ba6-6a23-4e5e-c9b8-08dc620999b8
X-Microsoft-Antispam-Untrusted: BCL:0;
X-Microsoft-Antispam-Message-Info-Original: =?us-ascii?Q?YhXZzyHns7J0bVpueFrYHBPp2UEDImkdvAO8mv/obyJxIHUzPNclKZsLm+L2?=
 =?us-ascii?Q?n9RpwnhzGeHy97FzbSwSxQgLRzrPJfKOFm9mg1Kxx3VNBmp03t0gPmDpIGTQ?=
 =?us-ascii?Q?ZNlNdP8Jl5DxNIFQSafS/h4EzdZl6nrj2rI2YDTCCVpdYK7nCeof2IM19LGC?=
 =?us-ascii?Q?3GBjOklLDEFxrT/SZz9DX+gu27YwVDB1VGYXQD6DV1eBL417FGQaAgzZeG0x?=
 =?us-ascii?Q?GgwJD1BNJ3LC+QzJOsmjXRqNjDdz2KtqcGvUEGCwtgiYtfYYq8x6JTI5DFdD?=
 =?us-ascii?Q?7zrFeaVkiJ3i2Mxo9pyQMOnjFEQl2Pb3kZaWE+XvhBImiHkOkNinrcFKZHRJ?=
 =?us-ascii?Q?8cbIv7DzcfHQcSfq/yiTXaTlrG08UpNXCSDhLcm9Qo+yD8/fbM0rc7uw+JW9?=
 =?us-ascii?Q?aW7skPUHkAAF8LmDvR/FDwIQGHarSHUmuyZfnOMKI/va9kwoj56tQt9zuDR5?=
 =?us-ascii?Q?0sl8qGbkRkSnuFiTwx5wI3RpWpbV1/t6kXIe0sR4EPlnWs3olsIPhl4a7ytk?=
 =?us-ascii?Q?Y61M6peqRWXbe8VJK3v/VZKMNujtJfK82YD/kYHSgFzw+nsTvBh2LjHzH+G2?=
 =?us-ascii?Q?5axSfWKnz0kI++LANLbPNhZcaUiz2nExS2rxhie9NLiv1CDLqBkR6MFKQuLZ?=
 =?us-ascii?Q?XDJ5OwY09fVidigTswGKi6biJXTjGiFRzYsiSLTJ2t67RgWmH5Eh0yQCOozS?=
 =?us-ascii?Q?EgaWklmLD6xvYyQxiGRbMRdkgt+fZFXqfXROGsfBE6Aq9aXsPSg1vIp9Txx9?=
 =?us-ascii?Q?1W05n/yay5rls8IlCjT8uYd2LuBqIRAb3odwtww4R1Pf+hemVp0OLDlf9y5W?=
 =?us-ascii?Q?q5nj5oPrTdecIk3UKrBbhPc8yENZO+qr0EUaBClgTjS+0acwQizT3G1by4qB?=
 =?us-ascii?Q?iTkiCQthfPECunjRYK0egUoEngXwJoJ19w3XyNhKv2jd3RVsqSsdMb7LodSP?=
 =?us-ascii?Q?nAPiBo1yNPdTP7rGOvNET+889A9TUVtvQ0tuHxnumxOJ1muU217KVxtlzjqw?=
 =?us-ascii?Q?AjqA3aBapiXD6U3NVlg+8qavkMq728PtZ+vfdmrO98ILGFRKaif9IJayex3H?=
 =?us-ascii?Q?wGTTzEHm4HqqFUzNzlbDz1zDrxF/s/FTfRGSPl0R9rYhELQxyGGd9lkN2GaR?=
 =?us-ascii?Q?u2CF8ej2/NRHlywWGBmkXLUseXY7rlNGAQSmD6yuqAfjBhkIupKACpzxglqq?=
 =?us-ascii?Q?hmuOmVILZ46HYJm9qKK+LgYVNBvjG738obxADujqpd91sPSE23ev/B38CPGu?=
 =?us-ascii?Q?acX0hMq7vWDnIc1ifnVh0mR0rSEvE+NU/7zJZBjjp1Ss2rv6a0ffe1fP+gXI?=
 =?us-ascii?Q?7zzS6y+BbT1YFN3Jk4OpSayp5gYxh0l48+7IPrK5dthawn+n5WyZPd8ZxlZ0?=
 =?us-ascii?Q?2GRxS1PF19K81TITKh/ccXYR4wvCxYZQnBAGFPo0L18bg4CUjGx5jfTzONE6?=
 =?us-ascii?Q?HEjkfeWzLhVeZy0/G/n3wEOepPO80D5U0LbyYPPAzJBLJYBGpxPs4d0ShK1t?=
 =?us-ascii?Q?GSapzIoOOAe5PQepQkgw5iUkFsnuP1o53tXceT6m/95840SYt8Lw8yM2PVss?=
 =?us-ascii?Q?4pNJINAWuQU6JJCdcxhY5yYhJi3lbaPSz16dY1rAc+KSsKbiqbMy6ZAtk0Ge?=
 =?us-ascii?Q?VJKd1JT49L5w27bPuZ1wqB18nw3665zDe2+K8CN6Hxcxj+QHrjDs24tX0Blf?=
 =?us-ascii?Q?UMvwztr0hZVcPW38QqsozeGRXMQZ1evclExNRx/u5FCJ1N1jNZ3s2cRJYqpv?=
 =?us-ascii?Q?AIYQR8rvu5pfltAqmJpRZDqch7Oi2H17kepOrIzvgQxvJF6aeu5e7Imuo60b?=
 =?us-ascii?Q?8EtWEs6UliCMfF28fydeE28fzW45k0weqa7HKmLXfsQmMhDOvz2r+UWz+c8b?=
 =?us-ascii?Q?pM15vntgS1tPyklSmeED9RBOAP0NrViIEeJBaZOc/cRkM7NRVGfeTs9S0ozw?=
 =?us-ascii?Q?oq/Df9E5HcdNymuRqrQdHjRxxuM5Ts/mL5//8athcubI29YIGqoeFdZbL2k4?=
 =?us-ascii?Q?MTyd?=
X-Forefront-Antispam-Report-Untrusted: CIP:104.47.51.232;CTRY:NL;LANG:en;SCL:1;SRV:;IPV:NLI;SFV:NSPM;H:EUR03-AM7-obe.outbound.protection.outlook.com;PTR:mail-am7eur03lp2232.outbound.protection.outlook.com;CAT:NONE;SFS:(13230031)(7093399003)(2040899004);DIR:INB;
X-MS-Exchange-Transport-CrossTenantHeadersStamped: AM9P193MB0856
X-MS-Exchange-Transport-CrossTenantHeadersStripped: DU2PEPF00028D0D.eurprd03.prod.outlook.com
X-MS-Exchange-Transport-CrossTenantHeadersPromoted: DU2PEPF00028D0D.eurprd03.prod.outlook.com
X-MS-PublicTrafficType: Email
X-MS-Office365-Filtering-Correlation-Id-Prvs:
	78823f5c-ae0b-4168-4430-08dc62099d3e
X-Microsoft-Antispam: BCL:0;
X-Microsoft-Antispam-Message-Info:
	=?us-ascii?Q?kwGchCt21+vB7CkzDRAC1Nz6SNGVmgjbVnKGVR2L88Rj28LvsvTitBsnmmrM?=
 =?us-ascii?Q?w+CsDHc0BcmWvV8ARWmbuHfrYWcxiTzmdr9dnvSV39wHeknn/iA8U5K8rJlT?=
 =?us-ascii?Q?FnmHxakHa5IRVAl3AEOMBNvxlGPh+5O1V8fRhbE4dxdwiLFW6sCqCS8qmNmD?=
 =?us-ascii?Q?k38ZBxvTtXaVp1XgGWlJqvTYIwXxM9LN6pVmgF841onhfifloR5RWr0qPt+p?=
 =?us-ascii?Q?T8Dlq3yFC8yzUE0u6/5Yqzn7yZOE+2NOnAQK14XWRw7mWY/0rlOHzpIcyi/G?=
 =?us-ascii?Q?12DQEWfF0MdPzV+P5A03q5BuTEX4QyPgfdnu+TKDt1M3id4DnclgoYwfNg68?=
 =?us-ascii?Q?5MHswj63dkKKavmE7CPVkcwVZPj+ls0+evaCzHnC1lvy6lEB6wfWsr5YgHFS?=
 =?us-ascii?Q?A1YzVqw7TQo9tBR5HHKE0noYU3nyuwUGenYwU/uvkkuxhnWH4EcgXFIk1zDn?=
 =?us-ascii?Q?Y6HygKkD0VAENyHb8YDuy87SKfNPGF37YzXFpn+fmybrT5o6DutfNtxjyQ11?=
 =?us-ascii?Q?y17CpHL0ax6wQNnGLrwGAaKhQcEiXhzJRZ5fjlYwO7yGZdb8apOvNCpzS5Wu?=
 =?us-ascii?Q?N/EQjG37WuoLjaWtkhvYlFR2jEbJ6tjzYXh+QNfM9tT/z+30DSln/SWBOg8t?=
 =?us-ascii?Q?/r4E9zctldx2OmPtdSb7B2+oTWUzI6BZSXvDeM5vKUUQmozj6dtakBjnDcAO?=
 =?us-ascii?Q?BeDp7RA1IXvsxDFaVwpfAxisW8MXrzbjrw/wXE1j5/fYg/460t1yxtBV5+XI?=
 =?us-ascii?Q?ssq73LRBF/hT6rTlVrB+gzdsDvbYktx/aAvxfpBN7yMFYGo8MmzWZRsmdgiZ?=
 =?us-ascii?Q?sHIETfxRqu+/jNqzyyWtjbRsNYP2PTi+TEI7URiz2IgLhFYRyyrRIp/QFWWg?=
 =?us-ascii?Q?empp84sTp7TZFFOFLBnbZQiKpSqVmSwImbaoJ8w/n1okcrRr3drLclYLYBJ+?=
 =?us-ascii?Q?pvcwFaGCEiHQLUUPviCdDYn6chaJH3EWRk21WzCQf61RHMLTejTbPkzJO3Po?=
 =?us-ascii?Q?zrOSRctJjbOonRQr7PMzjuBJZKEZgJYRKMO22i3o58seg0N/ZlSVkNicuVNT?=
 =?us-ascii?Q?hqui+GIjKxpRf5dqDdGFsTRWnD2w+2ke5+HAsCJFbKumeEMUXHK3SxEYVfUD?=
 =?us-ascii?Q?3jMr/kHa05hIQl6EAWk17yZHw18YGOmB+6kLdtuX4DjIVljAH5j59uM6eb8l?=
 =?us-ascii?Q?NUDQxUucMiYVOSYIN4G0LeGacs8bWRYSH32UBpL0I7ob+EJuvwa2aFMEspvd?=
 =?us-ascii?Q?ayTcwI78Igm823tFSiEn1PKbSX/24eSogKBE9CY4JqUClgn10MitcpZ1PHoo?=
 =?us-ascii?Q?/N9w5IMogGg5vbosAf/gxgwni6mqlchFRDpodm6UKHh6zpyBAbWlLUDqZNUe?=
 =?us-ascii?Q?TLY577oN2w9DPVSHhSf/tt28c8dX49ajIQ0JIhqiL3zvvFECXcBTCpI2DVWC?=
 =?us-ascii?Q?tfdIw3run4kFbGwSJTpyx2tSDJOdnmpr5mxuhSg0onifK4k2fwpJ+/mgQ2iw?=
 =?us-ascii?Q?OobbljfyJKrWClau57ZVw8+EN6oNVFMY5MAQ3k5Wkbng/OxtKwpVB5HC7rod?=
 =?us-ascii?Q?K0TBSkcJ3KoAQQOGMjNJ5I0zFkiOHE/kSR8sSPAQPbyo9uOsupCYXjwYIfpO?=
 =?us-ascii?Q?xm9bGfne0Uc8y3sgU5o8sTlNqyKCLGp3XV/jeroNb/2x4fQdTOHhX/U+A+IX?=
 =?us-ascii?Q?WF7+cwX5XyOOd/D3NdgtwaWXOji/uqSIEsaN/6FCDiGV38vKQC0pMy1vIAPx?=
 =?us-ascii?Q?2/fSMa01TvfcBUZStaSe6vYylxTejj8KGoH+CHe+0tLzKpnBSWAu4baLU5gq?=
 =?us-ascii?Q?iWZLaM8q9sWIYhdL4dIr3XxV2Q/+NLBQa0v9FidwT8xzvxRQI4rOF08aZoQ3?=
 =?us-ascii?Q?gxDUQX+j/sTqVNgktX5bMEKYD9cOPm1j5ht6gyOjcR01ijar1gLrK9a+pzbJ?=
 =?us-ascii?Q?R+q8r01pJMYrKpvntzzS/IBzYM8u0e/md4yPc8xrtrE=3D?=
X-Forefront-Antispam-Report:
	CIP:104.47.17.104;CTRY:IE;LANG:en;SCL:1;SRV:;IPV:NLI;SFV:NSPM;H:EUR05-DB8-obe.outbound.protection.outlook.com;PTR:mail-db8eur05lp2104.outbound.protection.outlook.com;CAT:NONE;SFS:(13230031)(7093399003)(2040899004);DIR:INB;
X-OriginatorOrg: sci-bono.co.za
X-MS-Exchange-CrossTenant-OriginalArrivalTime: 21 Apr 2024 13:47:46.1952
 (UTC)
X-MS-Exchange-CrossTenant-Network-Message-Id: cc51f39d-479c-40aa-44be-08dc6209a045
X-MS-Exchange-CrossTenant-Id: ac15f455-2df6-42bd-924f-102f0ec7acfb
X-MS-Exchange-CrossTenant-AuthSource:
	DU2PEPF00028D0D.eurprd03.prod.outlook.com
X-MS-Exchange-CrossTenant-AuthAs: Anonymous
X-MS-Exchange-CrossTenant-FromEntityHeader: Internet
X-MS-Exchange-Transport-CrossTenantHeadersStamped: AS8P193MB2064


Original-Recipient: rfc822;margeaux.groenewald@sci-bono.co.za
Final-Recipient: rfc822;margeaux.groenewald@sci-bono.co.za
Action: failed
Status: 5.4.14
Diagnostic-Code: smtp;554 5.4.14 Hop count exceeded - possible mail loop ATTR34 [DU2PEPF00028D13.eurprd03.prod.outlook.com 2024-04-21T13:47:53.142Z 08DC618C59ADCC5C]
Remote-MTA: dns;DU2PEPF00028D13.mail.protection.outlook.com



---------- Forwarded message ----------
From: tshingombe fiston <tshingombefiston@gmail.com>
To: tshigombekb@gmail.com, tshingombe fiston <tshingombefiston@gmail.com>, tshingombe tshitadi <tshitaditshingombe@gmail.com>, tahitaditshingombe@gmail.com, tshitaditshingombe@yahoo.fr, TSHINGOMBEKB TSHITADI <TSHINGOMBEKB@gmail.com>, info@sciebono.coza, margeaux.groenewald@sci-bono.co.za
Cc: 
Bcc: 
Date: Sun, 21 Apr 2024 15:47:16 +0200
Subject: Re: sciebono self discovery


On Sat, Apr 20, 2024 at 4:28 PM tshingombe fiston <tshingombefiston@gmail.com> wrote:



    On Sat, Apr 20, 2024 at 4:26 PM tshingombe fiston <tshingombefiston@gmail.com> wrote:



        On Sat, Apr 20, 2024 at 4:17 PM tshingombe fiston <tshingombefiston@gmail.com> wrote:

            [Type the company name]

            Project

            Workbook is a compilation of adapted formal assessment brief career-project exhibition  

             

            Tshingombe tshitadi  tshingombe  

            [Pick the date]

             

             

            Absract :  scie bono  career center  librairie  career  mentoring  discovery  assessment    engineering studie   fiedl    and technologie  

             

             

            1. Purpose: explanation career center expo science journey of self discovery.

             

            Workbook is a compilation of adapted formal assessment brief career

            -project exhibition 

             

            -Name : tshingombe Tshitadi

            -Date :17/04/2024

            Section A: subjects and studies

            Section B: skills and ability strengths

             Section C:my career interests

             Section D: preferred field of study

            Section my personality profiles

            F:work values 

            .-design assessment:

            -1.subject entry: A,

            A:[career electrical technical ]--[mathematics informatics  :B]---[motoring :C]--

            [Saqa award degree level: D]-- [Engineering electrical: E] --- [panel wiring: F], [Skill inventory: G]--[functionality transfer skill] and outcome’s. ---

            [Engineering technologies science studies [research Education and training arts audio visual technologies communication architecture Ana construction].

            -subject :key design 

            -10. print "a"

            -20. print "b"

            -30. print "c"

            -40. print  "d"

            -50. print "e"

            -60. print "f"

            -70. print "g"

            -80. Print. "h"

            -90. print "I"

            -100.print  "j"

            -110.print  "k"

            Sub

            __________________

            120. input  "a1"

            130.  input  "b1"

            140.  input   "c1"

            150.  input   "d1"

            160.  Input.  "e1"

            170.  input    "f1 "

            180.  Input.  " g1"

            190.  Input.   "H1"

            200.  Input.  "i1"

            210.  input   "j1"

            220.  input  "k1"

            Sub

            _________________

            230. output  ( "a1"+"b1"+"c1")

            240.output ("d1"+"e1"+"F1")

            250.output ("g1"+"H1+"I")

            260. Output (j)

            Sub

            ___________________

            270. if ;{"a1"+"b1"+"C1"}=1

            280. Else="t "_subject =next step

            290.if ;{"d1"+"e1"+"F1"}

            300.else" t " subject :next step

            310.{" g1" +"H1"+"I"}

            320.else

            330. If and . subject step =1

            340. Show :outcome display

            .350.  Next. .string will

            ____________________

             

            Projection: technologie outcom project career:

            Design circuit principle career explain diagram

            _____________________________

            Design logograms:.

             

             

             

            --------------------------------------------

            Designed Algorigramme.

             

             

             

            ---------------------------------------------

            Designed table:

             

            -a

             

            -----------------------------------------------

            Design technologie career psychometric Education:

            Variable

            -education training

            Sequence series port  impulsion contact mother feeder .

            Career total guidence learning CVS switch term work value way cluster selected box peer 

             

             

             

            -


            	

            Logic process 

            -----------------------------

            A=011111111111

            B=001111111111

            C=000111111111

            ___________________; convert binaries .dec

            D=000011111111

            E=000001111111

            F=000000111111

            -------------------------------

            G=000000011111

            H=000000001111

             I =000000000111

            -------------------------------

            J =000000000011

             K=000000000001

            -------------------------------

            L1=.                        1

            -------------------------------

            L2=.                         1

            --------------------------------

            L3=                           1

            ---------------------------------

            L4=.                          1

            ----------------------------------

             

            -Educ technologie career psychometrical

             :

            Education logic processes,code module

             

             Mode  phase  switch Variance; term

            ------------------------------------

            XA=011111111111

            XB=001111111111

            XC=000111111111 

                                                 ;sum =XA+XB+XC

            -----------------------------------

            XD=000011111111

            XE=000001111111

            XF=000000111111

                                                 ;sum=XD+XE+XF

            -----------------------------------

            XG=000000011111

            XH=000000001111

            XI =000000000111.  ; sum =xD+xh+xi

            ----------------------------------

            Xj= 000000000011, sum 

             Xj=000000000001

            ---------------------------------

                                            ;   Product switch

            -------------------------------

             

            .-Reder subject outcome: module week term allocation .phase transition outcome level career: elementary, intermediary, senior.  Current 

             

            -Conductor .semi -conductor switch key career learning: logic binaries code 

            Module subject average career guidance:

            -Module career  (sum "a"+"b"+"c") ;(sum "d"+"e"+"f");("g"+"h"+"I").;

             

            - Task career step operate logic input output module learning sum. Module phase elementary, phase subject ,

            Modulation scaling block career input ,output phase 

             

            -Phase A,phaseB,phaseC,phaseD,phaseE,

            PhaseF,phaseG,phase h,phase I, 

            -Activities:key learner

            ______________________

            Module: ligth resistor. Induction learner bulb :

             

            --------------------------------------

             

            Module :rectifier redresseur phase  angle ,diode  operator phase sum career 

            5v logic 1,0r logic 0 volt

            Diode code encode display :

            Resistor: 

             

            Module : phase career  amplificator career gain .module transistor,  % good average 

            -----------------------------------

             

            Module disc triac thyristor integrator circuit .

            Display subject . %  good 

            -------------------------------------

            .line linearise

             

            Control logic analysis

             asservissemnt:lineare band :

            --------------------------------+---+

            Loop input output level grade: sum compare career: equivenlent job input output: dividers job analyze function job task. Switch. Binary 

             


            	

            .task: modulation course subject entry criteria job selected key (phase a. Subject electrical) statement goal tech industry, psychotic electrical drawing project, method measure instrument. Electrical machine, electricity industries, mechanical workshop lab, language. Actuality   electrical grade bulletin service: .education technologies   total posting job output  internet ship level  grade 12  (and) /logic mathematics informatique  ms do's window ms work windows,  outcome certified statement award , attestation test motoring initiation special diesel essential  vehicle, statement , telecommunication, pedagogue technical subject prep. Math physic drawing technical  technologies mechanic electrical  logic,rwiten  sleek expression civism, electrotech , psycho  pedagogie,didactic special ,intro psychopedagogie, orientation professional, electromechanic  machine elect thermodyn chemical metalurgi statistics,

            -------------------

            Task phase :Ccma seta council labour , outcom -security

             

            Task phase:Engineering saqa n diploma

             

             subject engineering n diplome interpretation log : assessment 

            -panel electrical wiring 

            Subject  statement outcome: course module mathematics, engineering science,trade theory electrical , engineering drawings,:electrotech electrotech. National trade diploma

             

            , industrial electronics trade , average, assessment police ,

             career :

             

            Graduate program: Alison , Microsoft, schedule :,

            Ccma labour security officer,policy intelligence 

            Records

            ____________

            -modulation 3month 90 days allocation credit 360: term .

            Outcom career transmission generation 

            Graduate:post  senior 

             

            Total: faculty course total computing 

            -guidence  outcom generation: engineering  senior :engineering transmission dispatch custom +Dev op information ITC mathematics data science network path+special research motor +trainer training seniors educator technic ,job post subject ,  generalist A1,2,

             

             

            -sum a,b,c=.  ,sum ,d, e,f=.   sum= g,h,I:

             

            Asservissemnt synchronisation phase level equivenlent level  grade,phase Angela 3month  linear non linear scale synchronise , equivenlent trade, professional 

             


            	

            - task module reader 

            Modulation ,activity

            -Research operationel:method research career  implementation career join venture subject course tendered minimum close contractor  quotation compagny key learners  step A+B+C  

            Module 

            -research phase oscillator local signal A B .command  network services

            -display register key .plate  .display line pin address.vertical map, horizontal map AX=100000000000,AY=10000000000,

            Az=10000000000, , base synch 

            Amplificator operationel Ax,Ay,Az

            Resolve  variance ,covariance equation linear  ax+by+c=0, .ax°+by+c...ax+by+cz=O..

            Dimensionnement algorithm,scale

            -Research operationel

            -lecture  reading module activities career outcom disc task call recall career  module term  asservissemnt lineare  detector  convert base binairy.decimal  disc  detection Ax=1000000000,recall accumulation register key Ax,A,yAz,key to  flip flop amplificator lecture career move file read lecture captor analyser task .tap recording memory heater accumulation career.

             


            	


            Research map(xa,ya,az) operationel career work outcome :transited job duty functional line  Project key :

            Transfer :research intelligence artificial genie mil ,civil ,technical security instruction key duty ,safety health labour display.  Career intelligence re Engineering, outcome job opportunity scaling , coordination ordination axes x ,y,z, Cartesian projection  find job map transition 


            	

             

             

             

             

             

             

             

             

             

            2.  Referral librarie casebook photocopy project

            DISCOVERY CAREER   ;

             

            -JOB DISCOVERY LIBRARIE; BOOK JOB INVENTORY JOBCAREER CAREER

             

            -LEARNER DISCOVERY CAREER: JOB TOPIC CASE BOOK COMPAGNY 

            -FACILITATOR DISCOVERY CAREER: JOB TOPIC CASE BOOK   COMPAGNY AGREEMENT

             

            -LEARNER  NAME:………………………………………………………………………………………………………………………..

            -FACILITATOR:……………………………………………………………………………………………………………………………….

            NAME:…………………………………………………………………………………………………………………….;………………...

            -MODERATOR NAME:……………………………………………………………………………………………………………………….

             

            -ASSESSOR NAME:……………………………………………………………………………………………………………………………

            INSTITUTION NAME:…………………………………………………………………………………………………………………..

             

            HR:RESOURCE FRAMMEWORK:  CLOSE COMPAGNY 

            LIBRARIE PUBLIC   JHB:

            SCIEBONO CAREER CENTER LIBRARIE:

            COST PROJECT FILING:

             

             

             

             

             

             

             

             

             

             Tools assessment   librarie and material  assessment project librariecareer center

             

            ENTRY CRITERIA /TASK BOOKING MAGAZINE

            ID ORDER  BOOKING
            	

            TOPIC  BOOKING 
            	

            COST  BOOKING 
            	

            TOPIC PROJECT COST  COMPAGNY  DESIGN/ COMMENT   REVIEW

             

            WEB SITE:

             

             

             

             

             

             

             

             
            	

             
            	

             
            	

             

            NEWS PAPPER

             

             

             

             

             

             

             
            	

             
            	

             
            	

             


...

[Message clipped]  View entire message

		tshingombe scie bono project.docx
68K View as HTML Download
