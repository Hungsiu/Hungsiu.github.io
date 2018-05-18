---
layout: post
title: You're up and running!
---

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

```cs
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class ResetBall : MonoBehaviour
{
	void Start ()
	{
		
	}

	void Update ()
	{
		if (transform.position.y < -1) {
			gameObject.GetComponent<Rigidbody> ().velocity = Vector3.zero;
			Vector3 vector = new Vector3(Random.Range(-0.27f ,0.27f) ,1,Random.Range(0.15f ,0.40f));
			transform.position = vector;
		}
	}
}

```

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU5MzE0NTA0MywxNTkwNzQ3NjQ1LC0xND
g5NTAyMTEsMTU5MDc0NzY0NSwtMTA4Mjg4NDYwOSwxNTkwNzQ3
NjQ1XX0=
-->