---
title: "Module config"
title_tag: "Module config | Package @pulumi/github | Node.js SDK"
linktitle: "config"
meta_desc: "Explore members of the config module in the @pulumi/github package."
git_sha: "aebd24f06ba3c55158d70609bd8151cf5f5f7bd1"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/terraform-providers/terraform-provider-github)
> distributed under [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-github` repo](https://github.com/pulumi/pulumi-github/issues); however, if that doesn't turn up anything,
> please consult the source [`terraform-providers/terraform-provider-github` repo](https://github.com/terraform-providers/terraform-provider-github/issues).







<h3>APIs</h3>
<ul class="api">
    <li><a href="#anonymous"><span class="symbol api"></span>anonymous</a></li>
    <li><a href="#baseUrl"><span class="symbol api"></span>baseUrl</a></li>
    <li><a href="#individual"><span class="symbol api"></span>individual</a></li>
    <li><a href="#insecure"><span class="symbol api"></span>insecure</a></li>
    <li><a href="#organization"><span class="symbol api"></span>organization</a></li>
    <li><a href="#token"><span class="symbol api"></span>token</a></li>
</ul>




<h2 id="apis">APIs</h2>
<h3 class="pdoc-module-header" id="anonymous" data-link-title="anonymous">
    <a href="https://github.com/pulumi/pulumi-github/blob/aebd24f06ba3c55158d70609bd8151cf5f5f7bd1/sdk/nodejs/config/vars.ts#L13">
        let <strong>anonymous</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> anonymous: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;boolean&gt;(&#34;anonymous&#34;)</span>;</code></pre>

Authenticate without a token. When `anonymous`is true, the provider will not be able to access resourcesthat require
authentication.

<h3 class="pdoc-module-header" id="baseUrl" data-link-title="baseUrl">
    <a href="https://github.com/pulumi/pulumi-github/blob/aebd24f06ba3c55158d70609bd8151cf5f5f7bd1/sdk/nodejs/config/vars.ts#L17">
        let <strong>baseUrl</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> baseUrl: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;baseUrl&#34;) || (utilities.getEnv(&#34;GITHUB_BASE_URL&#34;) || &#34;https://api.github.com/&#34;)</span>;</code></pre>

The GitHub Base API URL

<h3 class="pdoc-module-header" id="individual" data-link-title="individual">
    <a href="https://github.com/pulumi/pulumi-github/blob/aebd24f06ba3c55158d70609bd8151cf5f5f7bd1/sdk/nodejs/config/vars.ts#L21">
        let <strong>individual</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> individual: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;boolean&gt;(&#34;individual&#34;)</span>;</code></pre>

Run outside an organization. When `individual`is true, the provider will run outside the scope of anorganization.

<h3 class="pdoc-module-header" id="insecure" data-link-title="insecure">
    <a href="https://github.com/pulumi/pulumi-github/blob/aebd24f06ba3c55158d70609bd8151cf5f5f7bd1/sdk/nodejs/config/vars.ts#L25">
        let <strong>insecure</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> insecure: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;boolean&gt;(&#34;insecure&#34;)</span>;</code></pre>

Whether server should be accessed without verifying the TLS certificate.

<h3 class="pdoc-module-header" id="organization" data-link-title="organization">
    <a href="https://github.com/pulumi/pulumi-github/blob/aebd24f06ba3c55158d70609bd8151cf5f5f7bd1/sdk/nodejs/config/vars.ts#L29">
        let <strong>organization</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> organization: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;organization&#34;) || utilities.getEnv(&#34;GITHUB_ORGANIZATION&#34;)</span>;</code></pre>

The GitHub organization name to manage. If `individual` is false, `organization` is required.

<h3 class="pdoc-module-header" id="token" data-link-title="token">
    <a href="https://github.com/pulumi/pulumi-github/blob/aebd24f06ba3c55158d70609bd8151cf5f5f7bd1/sdk/nodejs/config/vars.ts#L33">
        let <strong>token</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> token: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;token&#34;) || utilities.getEnv(&#34;GITHUB_TOKEN&#34;)</span>;</code></pre>

The OAuth token used to connect to GitHub. If `anonymous` is false, `token` is required.

