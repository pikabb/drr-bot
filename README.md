const Discord = require('discord.js');
const bot = new Discord.Client();

bot.on('message', (message) => {

    if(message.content == 'how to get on?') {
        message.reply('Copy paste this into your flash player! https://dangergun.github.io/webclient/dr/DRR.swf?env=loesoft-test');
    }

        if(message.content == 'hi') {
            message.reply('Greetings!');
        }

});

bot.login('Mzk2ODU3OTAzOTI5MzYwNDA0.DSn3Pg.cDN96UDOAQHFjp1432v47_P7im0');
