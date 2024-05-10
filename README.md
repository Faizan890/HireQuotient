+---------------+     +---------------+
|     User      |     |    Message    |
+---------------+     +---------------+
| - userId      |     | - messageId   |
| - username    |     | - senderId    |
| - email       |     | - recipientId |
| - password    |     | - content     |
| - status      |     | - timestamp   |
+---------------+     +---------------+
       |                     |
       |                     |
+---------------+     +---------------+
|   Conversation|     |     Room      |
+---------------+     +---------------+
| - conversationId|   | - roomId      |
| - participants  |   | - name        |
|                 |   | - participants|
+--------+-------+   +---------------+
         |
         |
+---------------+
|    ChatAPI    |
+---------------+
| - apiId       |
| - name        |
| - endpoint    |
+---------------+
Basic Appraoch One can use it 


