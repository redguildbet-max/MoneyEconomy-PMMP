Start your economy with our MoneyEconomy plugin, but what is MoneyEconomy?

MoneyEconomy is a brand new plugin for your PocketMine 5 servers, also known as PMMP5. This plugin adds a new economy system, administrative commands, and an API to your server.

For plugin developers, we have created a small but powerful API.

use MoneyEconomy\API\MoneyAPI;
$balance = $moneyAPI->getBalance($player);
$moneyAPI->transferMoney($from, $to, $amount);

Also in order that the plugin starts you need such requirements as 

PocketMine PMMP5 5.32.1
Minecraft Bedrock 1.21.100 - 1.21.101
FormAPI from jojoe77777
