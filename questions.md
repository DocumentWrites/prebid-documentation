---
layout: page_v2
title: Questions & FAQ
description: 

---

<div class="bs-docs-section" markdown="1">

# Questions

{: .text-center :}

## General questions, feature requests, or anything

<div class="form-horizontal">

  <div class="form-group">
    <label class="col-sm-2 control-label">Comment</label>
    <div class="col-sm-10">
      <textarea class="form-control" id="comment-field" rows="4" autofocus></textarea>
    </div>
  </div>

  <div class="form-group">
    <label class="col-sm-2 control-label">Site Link</label>
    <div class="col-sm-10">
      <input class="form-control" id="site-field" placeholder="https://" autofocus required>
    </div>
  </div>

  <div class="form-group">
    <label class="col-sm-2 control-label">Email</label>
    <div class="col-sm-10">
      <input class="form-control" placeholder="Email" id="email-field" required>
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-2 col-sm-10">
      <button class="btn btn-primary btn-lg" id="submit-comment" onclick="submitComment()">Send</button>
    </div>
  </div>
</div>

</div>
