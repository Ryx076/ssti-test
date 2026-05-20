api_test=${7?api!"NO_API"}
class_test=${request.class.name!"NO_CLASS"}
exec=<#assign ex="freemarker.template.utility.Execute"?new()>${ex("id")}
