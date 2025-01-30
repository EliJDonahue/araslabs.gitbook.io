# Create an Aras Innovator Object

You need an Aras Innovator Object to return a newResult() or newError() Item.



{% tabs %}
{% tab title="JavaScript" %}
```javascript
var myInnovator = new Innovator();
var myInnovator = this.getInnovator();
```
{% endtab %}

{% tab title="C#" %}
```csharp
Innovator myInnovator = this.getInnovator();
```
{% endtab %}
{% endtabs %}
