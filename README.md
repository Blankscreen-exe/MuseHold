# MuseHold
An opensource Patreon clone.

# Features

## Users
- users have three types of roles:
  - **Admin**: has all priviledges.
  - **Creator**: The content creators/artists who want to create a fanbase.
  - **Supporters**: The fans
- Each type of user has their own login form.
- Creators and Supporters both can maintain their profile page.
  - A Bio page where all of their personal details are displayed.
  - A Projects listing page exclusively for the creators.
- Blog roll
  - Content creators have an exclusive blog roll where they can post about their services or products.
  - Supporters will have a feed which contains all the latest posts by several different content creators (only of those which they have subscribed to).
- Email notification
  - Content creators will get a noification once a new supporter joins in.
  - Supporters will get a notification once the creator posts something new.
- Membership Tiers
  - Creators can setup membership tiers which the supporters can subscribe to.
  - Supporters are allowed to change their membership level or cancel subscription at any given time.
  - Creators can associate rewards for level of subscription tier.
- Payment processing
  - use Stripe or other robust payment gateways to implement money transactions from supporters to creators.
- Messaging system
  - Simple chat feature which enables supporters to contact their ideal creators while staying within the platform.
  - This chat can be initiated by the Supporters only as a one time invite to chat. If the Creator replys back to their message then the chat room will enable the supporter to send more messages.
  - If a creator initiates the chat, then both parties can send as many messages as they can.
- Reporting and Spam
  - Both creators and supporters have an option to report someone.
  - This report will be accompanied by a message in which the user describes why they are reporting an individual.
  - The reported message will be emailed to all the admins and will be saved in the database (also marked as "not resolved")  
