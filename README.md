# Merge PDF, Email and Excel files into a single PDF document with Aspose REST APIs
This [free consulting project](https://aspose-free-consulting.github.io/) uses Aspose Cloud REST APIs to merge PDF, Email and Excel files into a single PDF document using cURL command. Aspose Cloud REST APIs empower to manipulate 100+ Office File Formats on any platform that supports REST.

We will use merge these files using [Aspose.Email Cloud API](https://products.aspose.cloud/email), [Aspose.Words Cloud API](https://products.aspose.cloud/words), [Aspose.Cells Cloud API](https://products.aspose.cloud/cells) and [Aspose.PDF Cloud API](https://products.aspose.cloud/pdf) as follows. First, we will convert Email and Excel files to PDF and then will merge all the PDF documents into a single PDF document.

# Guidelines for Usage
**Sign up with Aspose Cloud:** First, create an account with [aspose.cloud](https://dashboard.aspose.cloud/#/) and get your Client Id and Client Secret to call Aspose REST APIs

**Get JSON Web Token Authentication:** Aspose APIs use [JSON Web Token for authentication](https://docs.aspose.cloud/total/json-web-token-authentication/) of API calls. You need to send a POST request to /connect/token endpoint by authenticating the request using Client Credentials (Client Id and Client Secret).

**Convert Email to PDF:** Aspose.Email Cloud API does not support direct conversion of Email to PDF. So we will first convert Email to MTHML using Aspose.Email Cloud API and later will convert MHTML to PDF using Aspose.Words Cloud API.

**Convert Excel to PDF:** We will convert the Excel file to PDF using Aspose.Cells Cloud API.

**Merge multiple PDF documents:** Finally, we will merge multiple PDF documents into a single PDF document using Aspose.PDF Cloud API.

# Interested in Aspose free consulting project?
[If you are also interested in a free consulting project by Aspose team then please view details on this page](https://aspose-free-consulting.github.io/)

If you have any questions about Aspose APIs, please feel free to [post your query in Aspose file format APIs Forums](https://forum.aspose.com/).

Also, you can keep in touch with the latest developments in [file format APIs offered by Aspose at our Blog](https://blog.aspose.com/).

# This free consulting project is based on the following issue:
[I want to render a PDF using another PDF, an email and an excel](https://github.com/aspose-free-consulting/projects/issues/55)
