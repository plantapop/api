# Chat API 1.0.0 documentation

## Table of Contents

* [Channels](#channels)




## Channels



<a name="channel-chat/{id}"></a>


#### Channel Parameters

##### id

ID of the chat

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Type</th>
      <th>Description</th>
      <th>Accepted values</th>
    </tr>
  </thead>
  <tbody>

<tr>
  <td>id </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>
    </tbody>
</table>




###  `publish` chat/{id}



#### Message


Send messages to a chat



##### Payload


<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Type</th>
      <th>Description</th>
      <th>Accepted values</th>
    </tr>
  </thead>
  <tbody>

<tr>
  <td>id </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>chatId </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>sender </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>content </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>timestamp </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr></tbody>
</table>


###### Example of payload _(generated)_

```json
{
  "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  "chatId": "f255124e-3419-4f6e-b7ee-17a6577db94d",
  "sender": "user@example.com",
  "content": "string",
  "timestamp": "2019-08-24T14:15:22Z"
}
```




###  `subscribe` chat/{id}



#### Message


Receive messages from a chat



##### Payload


<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Type</th>
      <th>Description</th>
      <th>Accepted values</th>
    </tr>
  </thead>
  <tbody>

<tr>
  <td>id </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>chatId </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>sender </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>content </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>timestamp </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr></tbody>
</table>


###### Example of payload _(generated)_

```json
{
  "id": "497f6eca-6276-4993-bfeb-53cbbbba6f08",
  "chatId": "f255124e-3419-4f6e-b7ee-17a6577db94d",
  "sender": "user@example.com",
  "content": "string",
  "timestamp": "2019-08-24T14:15:22Z"
}
```





<a name="channel-chat/{id}/receipts"></a>


#### Channel Parameters

##### id

ID of the chat

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Type</th>
      <th>Description</th>
      <th>Accepted values</th>
    </tr>
  </thead>
  <tbody>

<tr>
  <td>id </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>
    </tbody>
</table>




###  `publish` chat/{id}/receipts



#### Message


Send read receipts to a chat



##### Payload


<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Type</th>
      <th>Description</th>
      <th>Accepted values</th>
    </tr>
  </thead>
  <tbody>

<tr>
  <td>messageId </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>chatId </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>recipient </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr>

<tr>
  <td>timestamp </td>
  <td>string</td>
  <td> </td>
  <td><em>Any</em></td>
</tr></tbody>
</table>


###### Example of payload _(generated)_

```json
{
  "messageId": "8540d774-4863-4d2b-b788-4ecb19412e85",
  "chatId": "f255124e-3419-4f6e-b7ee-17a6577db94d",
  "recipient": "user@example.com",
  "timestamp": "2019-08-24T14:15:22Z"
}
```





