---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW VERSION OF THE SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new Community();
$requestBody->setDisplayName('Financial Advice for Software Engineers');
$requestBody->setDescription('A community where financial advisors who represent customers from software engineering profession can discuss advice and suggestions for their clients.');
$requestBody->setPrivacy(new CommunityPrivacy('public'));

$result = $graphServiceClient->employeeExperience()->communities()->post($requestBody)->wait();

```