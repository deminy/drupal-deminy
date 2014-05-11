This Drupal module contains various tweaks customized for personal website deminy.net.


* Tweak One: Redirect 403 pages caused during site migration from S9Y to Drupal.

  In year 2013 deminy.net was migrated from Serendipity to Drupal, leaving some
  old S9Y-generated blog URLs return HTTP 403 responses in Drupal.
 
  The tweak did in this module is: if a 403 response is triggered for a blog URL (URLs
  starting with /blog/*), then redirect either to home page or site map.
 

* Tweak Two: Add friendly note on the page where visitors might leave comments/posts.

  Due to heavy ad/spam posts happening daily, site deminy.net uses Mollom (or similar
  intelligent content moderation service/module) to filter user comments/posts. Because
  of this, user comments/posts may not be displayed immediately once posted when the post
  is detected as possible ad/spam.

  The tweak is to add a user-friendly message on the form notifying visitors that their
  comments/posts may not be displayed immediately.
