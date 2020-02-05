MimicBot -> Mimics everything that is said.

For Extra Credit, I have tried to fashion my MimicBot as a message encoder. 
Assuming each user input is a text message, my bot outputs an encoded form of that message.

Mimic Bot is an Alexa skill that starts up on inputing 'mimic bot' in the Alexa Test tab of the Alexa development console.

E.g.   
          
             Skill ID -> amzn1.ask.skill.c78ef217-08ad-41c3-bb44-7e6b7b845169
            Skill Name-> hello-alexa

       Alexa Endpoint -> arn:aws:lambda:us-east-1:741865522592:function:c78ef217-08ad-41c3-bb44-7e6b7b845169:Release_0
       
       
          
          User Input  : mimic bot
    MimicBot's Output : Welcome! This is an Alexa Echo skill!



          User Input  : the world is burning, where are you?
    MimicBot's Output : Your message, 'the world is burning, where are you'. 
                        Word Count : 7 , Letter Count : 29 , 
                        Encoded message : rsia t rhnyl uweb owiugenr, oehdre
