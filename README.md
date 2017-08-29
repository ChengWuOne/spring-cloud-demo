# micro-service
spring-cloud 微服务组件demo

<table>
<tbody><tr>
<td>工程名</td>  <td>描述</td>  <td>端口</td>
</tr>
<tr>
<td>eureka-server</td>  <td>服务发现与注册中心</td>  <td>7071</td>
</tr>
<tr>
<td>ribbon</td>  <td>负载均衡器</td>  <td>7072</td>
</tr>
<tr>
<td>zuul</td>  <td>动态路由器</td>  <td>7073</td>
</tr>
<tr>
<td>service-A</td>  <td>A服务，实现两个数相加，用来测试服务间调用与路由</td>  <td>2222</td>
</tr>
<tr>
<td>service-B2</td>  <td>B2服务，实现两个数相减，用来测试负载均衡和微服务的调用与路由</td>  <td>7078</td>
</tr>
  <tr>
<td>service-B3</td>  <td>B3服务，和B2服务一样的，实现两个数相减，用来测试负载均衡和微服务之间的调用与路由</td>  <td>7079</td>
</tr>
</tbody></table>
