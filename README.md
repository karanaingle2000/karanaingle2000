<%@ Page Language="vb" AutoEventWireup="false" CodeBehind="F1.aspx.vb" Inherits="Dress_up.F1" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <title></title>
    <style>
        .grid-container{
            display:inline-table;
            right:120px;
            
            
        }
        div.relative {
            text-align :start;
            padding:25px;
            right:15px;

        }

        div.absolute {
            text-align:center;
             position: relative;
             top: 80px;
             right:auto;
            
             width: 600px;
             height: 500px;
             border: 3px solid #73AD21;

        }

    </style>
</head>
<body>
    <form id="form1" runat="server">
        <div class="grid-container">
            <div class="absolute">
            <button > <a href="javascript:alert('Hello Karan!');">hi</a></button>

            </div>
            <div>
                <button><a href="mailto:karanaingle2000@gmail.com">send mail</a></button>
            </div>
            <div class="relative">
                <button><a href="tel:+919022895592">call karan</a></button>
            </div>
            <div>
                <p>the <abbr title="world health orgnition">WHO</abbr>is found in 1948 in usa.</p>
            </div>

        </div>
    </form>
</body>
</html>
