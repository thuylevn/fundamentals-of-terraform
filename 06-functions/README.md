# Module 9 - Functions
[Terraform Functions Documentation](https://www.terraform.io/docs/configuration/functions.html)

```shell script
$ terraform console
> max(5, 12, 9)
> file("example.json")
> jsondecode(file("example.json"))
> length(jsondecode(file("example.json")))
> keys(jsondecode(file("example.json")))
> jsondecode(file("example.json")).colors
> length(jsondecode(file("example.json")).colors)
> keys(jsondecode(file("example.json")).colors)
> keys(jsondecode(file("example.json")).colors[0])
```
## Additional Resources
[Terraform Functions Documentation](https://www.terraform.io/docs/configuration/functions.html)