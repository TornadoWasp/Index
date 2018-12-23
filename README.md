# Indexconst Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
});

client.on("guildMemberAdd" , function(member)
{
  member.send("**You Have Joined The Cheat Nation ARMY! Please Follow The Rules.**");
  member.send("**Please Give The Owner Username And Password Then He Will Send You A Code If You Want A Customizable Code Its For 1$ If Not Customizable Code Its Free.**");
  member.send(":regional_indicator_c: :regional_indicator_h: :regional_indicator_e: :regional_indicator_a: :regional_indicator_t:  ");
  member.send(":regional_indicator_n: :regional_indicator_a: :regional_indicator_t: :regional_indicator_i: :regional_indicator_o: :regional_indicator_n: ")
});

client.on('message', function(message){
  if(message.content == '0817') //Theblue1gamer

 {

  message.member.send("**You Have Been Logged In**");
  let memberRole = message.member.guild.roles.find("name", "Signed In");
  message.member.addRole(memberRole);
  message.delete()
 }

});

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
});



client.on('message', function(message){
  if(message.content == '0801') // joker_sb3

 {

  message.member.send("**You Have Been Logged In**");
  let memberRole = message.member.guild.roles.find("name", "Signed In");
  message.member.addRole(memberRole);
  message.delete()
 }

});

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
});

client.on('message', msg => {
  if (msg.content === '!how to sign up') {
    msg.reply('**You Can Sign Up By Dming The Owner Username And Password Then You Wil Be Sent With 4 Digit Code Then This Is The Code To Sign In With**');
  }
});

client.on('message', function(message){
  if(message.content == '0848') // G O D O W N

 {

  message.member.send("**You Have Been Logged In**");
  let memberRole = message.member.guild.roles.find("name", "Signed In");
  message.member.addRole(memberRole);
  message.delete()
 }

});

client.on('message', function(message){
  if(message.content == '0849') //Khost

 {

  message.member.send("**You Have Been Logged In**");
  let memberRole = message.member.guild.roles.find("name", "Signed In");
  message.member.addRole(memberRole);
  message.delete()
 }


});

client.on('message', function(message){
  if(message.content == '0888') //YeetSquad Mute

 {

  message.member.send("**You Have Been Logged In**");
  let memberRole = message.member.guild.roles.find("name", "Signed In");
  message.member.addRole(memberRole);
  message.delete()
 }


});





client.on('message', function(message){
  if(message.content == '106005') // CO Owner Sign Up And Text Messages

 {

  message.member.send("**You Have Been Logged In As A CO Owner**");
  let memberRole = message.member.guild.roles.find("name", "CO Owner");
  message.member.send("**Your CO Owner Code Is : !235236euyq12341dw1451204150w0**");
  message.member.addRole(memberRole);
  message.delete()
 }

});


client.on('message', function(message){
  if(message.content == '!235236euyq12341dw1451204150w0') //CO Log in

 {

  message.member.send("**You Have Been Logged In As A CO Owner**");
  let memberRole = message.member.guild.roles.find("name", "CO Owner");
  message.member.sendMessage("**Bot Coded By : TornadoWasp**");
  message.member.addRole(memberRole);
  message.delete()
 }

});

client.on('message', function(message){
  if(message.content == '!help') //Help Command

 {

  message.member.send("**Hey! The Cheat Nation Discord Was Made By TornadoWasp Who Is The Owner. He Does Everything.**");
  message.member.sendMessage("**If You Want To Sign Up Give Him A Username And A Password Without Saying Hello Then He Will Put Your Username and Password in His Sign Up Data Base.**");
  message.member.sendMessage("**Custom Code 1$, The Free Code Will Not Be Customizable.**");
  message.member.send(":regional_indicator_c: :regional_indicator_h: :regional_indicator_e: :regional_indicator_a: :regional_indicator_t:  ");
  message.member.send(":regional_indicator_n: :regional_indicator_a: :regional_indicator_t: :regional_indicator_i: :regional_indicator_o: :regional_indicator_n: ")
  message.delete()
 }

});






client.login('NTI2MDUzMzM2NDQxNTUyOTE2.DwFIYA.GoFlUug-VzZ9zMQynhVnEWZkKWs');
{
  "name": "my-bot",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "dependencies": {
    "discord.js": "^11.4.2",
    "fs": "0.0.1-security"
  },
  "devDependencies": {},
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Cheat Nation",
  "license": "ISC"
}

{
  "name": "my-bot",
  "version": "1.0.0",
  "lockfileVersion": 1,
  "requires": true,
  "dependencies": {
    "async-limiter": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/async-limiter/-/async-limiter-1.0.0.tgz",
      "integrity": "sha512-jp/uFnooOiO+L211eZOoSyzpOITMXx1rBITauYykG3BRYPu8h0UcxsPNB04RR5vo4Tyz3+ay17tR6JVf9qzYWg=="
    },
    "discord.js": {
      "version": "11.4.2",
      "resolved": "https://registry.npmjs.org/discord.js/-/discord.js-11.4.2.tgz",
      "integrity": "sha512-MDwpu0lMFTjqomijDl1Ed9miMQe6kB4ifKdP28QZllmLv/HVOJXhatRgjS8urp/wBlOfx+qAYSXcdI5cKGYsfg==",
      "requires": {
        "long": "^4.0.0",
        "prism-media": "^0.0.3",
        "snekfetch": "^3.6.4",
        "tweetnacl": "^1.0.0",
        "ws": "^4.0.0"
      }
    },
    "fs": {
      "version": "0.0.1-security",
      "resolved": "https://registry.npmjs.org/fs/-/fs-0.0.1-security.tgz",
      "integrity": "sha1-invTcYa23d84E/I4WLV+yq9eQdQ="
    },
    "long": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/long/-/long-4.0.0.tgz",
      "integrity": "sha512-XsP+KhQif4bjX1kbuSiySJFNAehNxgLb6hPRGJ9QsUr8ajHkuXGdrHmFUTUUXhDwVX2R5bY4JNZEwbUiMhV+MA=="
    },
    "prism-media": {
      "version": "0.0.3",
      "resolved": "https://registry.npmjs.org/prism-media/-/prism-media-0.0.3.tgz",
      "integrity": "sha512-c9KkNifSMU/iXT8FFTaBwBMr+rdVcN+H/uNv1o+CuFeTThNZNTOrQ+RgXA1yL/DeLk098duAeRPP3QNPNbhxYQ=="
    },
    "safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g=="
    },
    "snekfetch": {
      "version": "3.6.4",
      "resolved": "https://registry.npmjs.org/snekfetch/-/snekfetch-3.6.4.tgz",
      "integrity": "sha512-NjxjITIj04Ffqid5lqr7XdgwM7X61c/Dns073Ly170bPQHLm6jkmelye/eglS++1nfTWktpP6Y2bFXjdPlQqdw=="
    },
    "tweetnacl": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/tweetnacl/-/tweetnacl-1.0.0.tgz",
      "integrity": "sha1-cT2LgY2kIGh0C/aDhtBHnmb8ins="
    },
    "ws": {
      "version": "4.1.0",
      "resolved": "http://registry.npmjs.org/ws/-/ws-4.1.0.tgz",
      "integrity": "sha512-ZGh/8kF9rrRNffkLFV4AzhvooEclrOH0xaugmqGsIfFgOE/pIz4fMc4Ef+5HSQqTEug2S9JZIWDR47duDSLfaA==",
      "requires": {
        "async-limiter": "~1.0.0",
        "safe-buffer": "~5.1.0"
      }
    }
  }
}
