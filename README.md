# Bot::Backbone::Service::JabberChat

This is a chat service part of the Bot::Backbone chatbot ecosystem. It provides
a service for connecting to XMPP (aka Jabber) servers. This provides services
for connecting to group chats (called MUCs or multi-user chats in XMPP
parlance) and interacting with users via instant message.

The preferred installation would be to fetch it from CPAN:

    cpanm Bot::Backbone::Service::JabberChat

or if you don't have App::cpanminus installed (you should), you can run:

    perl -MCPAN -e 'install Bot::Backbone::Service::JabberChat'
