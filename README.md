# CSS Columns with OptimizePress

You can see the CSS [here](https://github.com/gMagicScott/great-scot-the-magic-dude/blob/gh-pages/css/main.css)

## First Form
```html
<form class="crmagicform" name="pricing-form" method="post" action="http://www.mcssl.com/app/contactsave.asp">
    <input name="merchantid" type="hidden" id="merchantid" value="96591" />
    <input name="ARThankyouURL" type="hidden" id="ARThankyouURL" value="http://greatscotthemagicdude.com/new/party-packages/.php" />
    <input id="defaultar" type="hidden" name="defaultar" value="984825" />
    <input name="copyarresponse" type="hidden" id="copyarresponse" value="0" />
    <input name="allowmulti" type="hidden" id="allowmulti" value="0" />
    <input name="visiblefields" type="hidden" id="visiblefields" value="Name,Email1" />
    <input name="requiredfields" type="hidden" id="requiredfields" value="Email1" />

    <div class="form-group">
        <label for="Name">What&apos;s your name?</label>
        <small>&nbsp;</small>
        <input type="text" id="Name" name="Name">
    </div>

    <div class="form-group">
        <label for="Email1">What's your email address?</label>
        <small>This is where I will send the package info & the Birthday Party Guide.</small>
        <input type="email" id="Email1" name="Email1">
    </div>

    <div class="form-group">
        <label for="field12">What is the bday child’s name? <font color="#0099FF">(FIRST NAME ONLY)</font></label>
        <small>If you are celebrating more than one bday, please enter both children’s names.</small>
        <input type="text" id="field12" name="field12">
    </div>

    <div class="form-group">
        <label for="gender">Is this birthday party for a boy, a girl or more than 1 birthday child?</label>
        <small>&nbsp;</small>
        <select name="field14" id="gender">
            <option value="0">Please choose a gender…</option>
            <option value="Boy">One Birthday Boy</option>
            <option value="Girl">One Birthday Girl</option>
            <option value="Multi">More Than One Birthday Child</option>
        </select>
    </div>

    <div class="form-group">
        <label for="field6">How did you find me?</label>
        <small>&nbsp;</small>
        <input name="field6" id="field6" type="text">
    </div>

    <div class="form-group submit">
        <input type="Submit" name="cmdSubmit" value="Get Info!">
    </div>

</form>
```

## Second Form
```html
<form class="crmagicform" name="pricing-form" method="post" action="http://www.mcssl.com/app/contactsave.asp">
    <input name="merchantid" type="hidden" id="merchantid" value="96591" />
    <input name="ARThankyouURL" type="hidden" id="ARThankyouURL" value="http://greatscotthemagicdude.com/new/party-packages/.php" />
    <input id="defaultar" type="hidden" name="defaultar" value="984825" />
    <input name="copyarresponse" type="hidden" id="copyarresponse" value="0" />
    <input name="allowmulti" type="hidden" id="allowmulti" value="0" />
    <input name="visiblefields" type="hidden" id="visiblefields" value="Name,Email1" />
    <input name="requiredfields" type="hidden" id="requiredfields" value="Email1" />
    <div class="form-row">
        <div class="form-group half">
            <label for="Name">What&apos;s your name?</label>
            <small>&nbsp;</small>
            <input type="text" id="Name" name="Name">
        </div>

        <div class="form-group half">
            <label for="Email1">What's your email address?</label>
            <small>This is where I will send the package info & the Birthday Party Guide.</small>
            <input type="email" id="Email1" name="Email1">
        </div>
    </div>
    <div class="form-row">
        <div class="form-group half">
            <label for="field12">What is the bday child’s name? <font color="#0099FF">(FIRST NAME ONLY)</font></label>
            <small>If you are celebrating more than one bday, please enter both children’s names.</small>
            <input type="text" id="field12" name="field12">
        </div>

        <div class="form-group half">
            <label for="gender">Is this birthday party for a boy, a girl or more than 1 birthday child?</label>
            <small>&nbsp;</small>
            <select name="field14" id="gender">
                <option value="0">Please choose a gender…</option>
                <option value="Boy">One Birthday Boy</option>
                <option value="Girl">One Birthday Girl</option>
                <option value="Multi">More Than One Birthday Child</option>
            </select>
        </div>
    </div>
    <div class="form-group">
        <label for="field6">How did you find me?</label>
        <small>&nbsp;</small>
        <input name="field6" id="field6" type="text">
    </div>

    <div class="form-group submit">
        <input type="Submit" name="cmdSubmit" value="Get Info!">
    </div>
</form>
```

## Third Form
```html
<form class="crmagicform" name="acontact-form" method="post" action="http://www.mcssl.com/app/contactsave.asp">
    <input name="merchantid" type="hidden" id="merchantid" value="96591" />
    <input name="ARThankyouURL" type="hidden" id="ARThankyouURL" value="http://greatscotthemagicdude.com/new/message-sent/.php" />
    <input name="copyarresponse" type="hidden" id="copyarresponse" value="0" />
    <input id="defaultar" type="hidden" name="defaultar" value="984818" />
    <input name="allowmulti" type="hidden" id="allowmulti" value="0" />
    <input name="visiblefields" type="hidden" id="visiblefields" value="Name,Email1" />
    <input name="requiredfields" type="hidden" id="requiredfields" value="Email1" />
    <div class="form-row">
        <div class="form-group half">
            <label for="contact-name" class="sr-only">Your name</label>
            <input name="Name" type="text" id="contact-name" placeholder="NAME" />
        </div>

        <div class="form-group half">
            <label for="contact-email" class="sr-only">Your best email address</label>
            <input name="Email1" type="email" id="contact-email" placeholder="EMAIL" />
        </div>
    </div>
    <div class="form-group">
        <label for="contact-subject" class="sr-only">Subject for your message</label>
        <input name="subject" type="text" id="contact-subject" placeholder="SUBJECT" />
    </div>

    <div class="form-group">
        <label for="contact-message" class="sr-only">Subject for your message</label>
        <textarea name="message" type="text" id="contact-message" placeholder="Enter text here&hellip;"></textarea>
    </div>

    <div class="form-group submit">
        <input type="Submit" name="cmdSubmit" value="Send Message" />
    </div>

</form>
```
