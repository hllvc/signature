# HTML Signature
### !! ONLY WORKS WITH EMAIL APPS THAT SUPPORT HTML SIGNATURE

Tested in [Mailspring](https://getmailspring.com/) ( *recommended* ) and also [Outlook](https://outlook.live.com/mail/) in web browser.

## Info

Email signature written in html using html tables. All parts of signature are made of pictures which are hosted on [Imgur](https://imgur.com/).
Pure concept is created in [Figma](https://figma.com/) and exported to `.png` in parts. Then table is created in html and data is filled with thoose pictures.
Only some icons that contain additional redirection on click are included as icons. Like Github, LinkedIn, Reddit ...

### Example

```
<!-- td inside main table -->
<td>
  <!-- creating another table for icons -->
  <table>
    <!-- adding one row -->
    <tr>
      <!-- putting each icon in separate td -->
      <td>
        <a href="link"><img src="icond"></a>
      </td>
      <td>
        <a href="link"><img src="icond"></a>
      </td>
      .
      .
      .
      
    </tr>
  </table>
</td>
```
### To place it in *Outlook*
* first go to your [Outlook Settings](https://outlook.live.com/mail/0/options/mail/messageContent),
* if link above does not work or you don't see signature field here is explanation with pictures,

![text](https://i.imgur.com/toeB6eO.png)

* then open [signature.html](signature.html) in web browser,
* copy all content with `Ctrl+A` then `Ctrl+C`,
* and just paste it in signature field `Ctrl+V`

### For mailspring it's easy
* just copy all html content from [signature.html](signature.html)
* in mailspring hit `Ctrl+,`
* go to mailspring *Signatures* tab and paste it in *Raw Source*

![text](https://i.imgur.com/UTz8hgH.png)

## Additional Info
#### Not yet suitable for mobile devices, works nice in landscape in some email apps.
