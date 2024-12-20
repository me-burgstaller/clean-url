# CleanUrl

<?php

require 'vendor/autoload.php';
use Cocur\Slugify\Slugify;

$url = new \MeBurgstaller\CleanUrl\MyUrl();
echo $url->slugify('https://example.org', 'Das ist ein langer Text.');
