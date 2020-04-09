
---
title: "RouteEntry"
block_external_search_index: true
---






## Create a RouteEntry Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/vpc/#RouteEntry">RouteEntry</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/vpc/#RouteEntryArgs">RouteEntryArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">RouteEntry</span><span class="p">(resource_name, opts=None, </span>destination_cidrblock=None<span class="p">, </span>name=None<span class="p">, </span>nexthop_id=None<span class="p">, </span>nexthop_type=None<span class="p">, </span>route_table_id=None<span class="p">, </span>router_id=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewRouteEntry<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/vpc?tab=doc#RouteEntryArgs">RouteEntryArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/vpc?tab=doc#RouteEntry">RouteEntry</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Vpc.RouteEntry.html">RouteEntry</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Vpc.RouteEntryArgs.html">RouteEntryArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Destination<wbr>Cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nexthop<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nexthop<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Route<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Router<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Destination<wbr>Cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nexthop<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nexthop<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Route<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Router<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>destination<wbr>Cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nexthop<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nexthop<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>route<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>router<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>destination_<wbr>cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nexthop_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nexthop_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>route_<wbr>table_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>router_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}







## RouteEntry Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Destination<wbr>Cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Nexthop<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Nexthop<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Route<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>Router<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Destination<wbr>Cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Nexthop<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Nexthop<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Route<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>Router<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>destination<wbr>Cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>nexthop<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>nexthop<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>route<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>router<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>destination_<wbr>cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>nexthop_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>nexthop_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>route_<wbr>table_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property- property-deprecated"
            title=", Deprecated">
        <span>router_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}








## Look up an Existing RouteEntry Resource

Get an existing RouteEntry resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/vpc/#RouteEntryState">RouteEntryState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/vpc/#RouteEntry">RouteEntry</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>destination_cidrblock=None<span class="p">, </span>name=None<span class="p">, </span>nexthop_id=None<span class="p">, </span>nexthop_type=None<span class="p">, </span>route_table_id=None<span class="p">, </span>router_id=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetRouteEntry<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/vpc?tab=doc#RouteEntryState">RouteEntryState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/vpc?tab=doc#RouteEntry">RouteEntry</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Vpc.RouteEntry.html">RouteEntry</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Vpc.RouteEntryState.html">RouteEntryState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Destination<wbr>Cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nexthop<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nexthop<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Route<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Router<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Destination<wbr>Cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nexthop<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Nexthop<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Route<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Router<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>destination<wbr>Cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nexthop<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nexthop<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>route<wbr>Table<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>router<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>destination_<wbr>cidrblock</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The RouteEntry's target network segment.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the route entry. This name can have a string of 2 to 128 characters, must contain only alphanumeric characters or hyphens, such as "-",".","_", and must not begin or end with a hyphen, and must not begin with http:// or https://.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nexthop_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The route entry's next hop. ECS instance ID or VPC router interface ID.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>nexthop_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The next hop type. Available values:
- `Instance` (Default): Route the traffic destined for the destination CIDR block to an ECS instance in the VPC.
- `RouterInterface`: Route the traffic destined for the destination CIDR block to a router interface.
- `VpnGateway`: Route the traffic destined for the destination CIDR block to a VPN Gateway.
- `HaVip`: Route the traffic destined for the destination CIDR block to an HAVIP.
- `NetworkInterface`: Route the traffic destined for the destination CIDR block to an NetworkInterface.
- `NatGateway`: Route the traffic destined for the destination CIDR block to an Nat Gateway.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>route_<wbr>table_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the route table.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>router_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This argument has beeb deprecated. Please use other arguments to launch a custom route entry.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Attribute router_id has been deprecated and suggest removing it from your template.{{% /md %}}</p></dd>

</dl>
{{% /choosable %}}











<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-alicloud">https://github.com/pulumi/pulumi-alicloud</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    
</dl>
