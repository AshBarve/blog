---
layout: post
title:  "Welcome to Jekyll!"
author: johndoe
categories: jekyll update
---

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight swift %}
//
//  ViewController.swift
//  BowlingGame
//

import UIKit

class ViewController: UIViewController {
  
  @IBOutlet weak var btnStartGame: UIButton!
  @IBOutlet weak var btnSubmitKnocks: UIButton!

  @IBOutlet weak var lblCurrentFrame: UILabel!
  @IBOutlet weak var lblCurrentRollNumber: UILabel!
  @IBOutlet weak var lblCumulativeScore: UILabel!

  @IBOutlet weak var txtPinsKnocked: UITextField!

  var automaticBowlingScorer = AutomaticBowlingScorer()

  override func viewDidLoad() {
    super.viewDidLoad()
    // Do any additional setup after loading the view, typically from a nib.
    resetGame()
  }
}
{% endhighlight %}



{% highlight swift %}
import Contacts

let contact = CNMutableContact()
contact.givenName = "Johnny"
contact.familyName = "Appleseed"
contact.emailAddresses = [
    CNLabeledValue(label: CNLabelWork,
                   value: "johnny@apple.com")
]

{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
