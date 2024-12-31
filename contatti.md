---
layout: post
title: Contatti
---


<!--
<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Send">
</form>
-->

<p class="mb-4">Inviaci il tuo messaggio tramite questo form: risponderemo il prima possibile!</p>
  <form target="_blank" action="https://formsubmit.co/nelidemaria.quarato@gmail.com" method="POST">
    <div class="form-group">
      <div class="form-row">
        <div class="col">
          <input type="text" name="name" class="form-control" placeholder="Nome *" required>
        </div>
        <div class="col">
          <input type="email" name="email" class="form-control" placeholder="Indirizzo email *" required>
        </div>
      </div>
    </div>
    <div class="form-group">
      <textarea placeholder="Il tuo messaggio *" class="form-control" name="message" rows="10" required></textarea>
    </div>
    <button type="submit" class="btn btn-lg btn-dark btn-block">Invia</button>
    <input type="hidden" name="_subject" value="Nuovo messaggio dal form di contatto di nelide.github.io!">
    <input type="hidden" name="_template" value="table">
    <input type="hidden" name="_autoresponse" value="Ecco il messaggio che hai lasciato su nelide.eu!">
  </form>