Type Switch
===========

Type switch syntax tree.

-	`*ast.Expr`
	-	[ast.BadExpr](./ast/BadExpr.md)
	-	[ast.Ident](./ast/Ident.md)
		-	Obj: [`ast.Object`](./ast/Object.md)
			-	[`ast.Decl`](./ast/Decl.md)
				-	[`ast.Field`](./ast/Field.md)
				-	[`ast.ImportSpec`](./ast/ImportSpec.md)
				-	[`ast.TypeSpec`](./ast/TypeSpec.md)
				-	[`ast.ValueSpec`](./ast/ValueSpec.md)
				-	[`ast.FuncDecl`](./ast/FuncDecl.md)
				-	[`ast.LabeledStmt`](./ast/LabeledStmt.md)
				-	[`ast.AssignStmt`](./ast/AssignStmt.md)
				-	[`ast.Scope`](./ast/Scope.md)
	-	[ast.Ellipsis](./ast/Ellipsis.md)
	-	[ast.BasicLit](./ast/BasicLit.md)
	-	[ast.FuncLit](./ast/FuncLit.md)
	-	[ast.CompositeLit](./ast/CompositeLit.md)
	-	[ast.ParenExpr](./ast/ParenExpr.md)
	-	[ast.SelectorExpr](./ast/SelectorExpr.md)
	-	[ast.IndexExpr](./ast/IndexExpr.md)
	-	[ast.SliceExpr](./ast/SliceExpr.md)
	-	[ast.TypeAssertExpr](./ast/TypeAssertExpr.md)
	-	[ast.CallExpr](./ast/CallExpr.md)
	-	[ast.StarExpr](./ast/StarExpr.md)
	-	[ast.UnaryExpr](./ast/UnaryExpr.md)
	-	[ast.BinaryExpr](./ast/BinaryExpr.md)
	-	[ast.KeyValueExpr](./ast/KeyValueExpr.md)
	-	[ast.ArrayType](./ast/ArrayType.md)
	-	[ast.StructType](./ast/StructType.md)
	-	[ast.FuncType](./ast/FuncType.md)
	-	[ast.InterfaceType](./ast/InterfaceType.md)
	-	[ast.MapType](./ast/MapType.md)
	-	[ast.ChanType](./ast/ChanType.md)
-	`ast.Decl`
	-	[ast.BadDecl](./ast/BadDecl.md)
	-	[ast.GenDecl](./ast/GenDecl.md)
		-	Token [token.Token (godoc.org)](https://godoc.org/go/token#Token)
			-	[`token.IMPORT` (godoc.org)](https://godoc.org/go/token#IMPORT)
			-	[`token.CONST` (godoc.org)](https://godoc.org/go/token#CONST)
			-	[`token.TYPE` (godoc.org)](https://godoc.org/go/token#TYPE)
			-	[`token.VAR` (godoc.org)](https://godoc.org/go/token#VAR)
		-	Specs [[ ]ast.Specs](./ast/Spec.md)
			-	[`ast.ImportSpec`](./ast/ImportSpec.md)
			-	[`ast.TypeSpec`](./ast/TypeSpec.md)
			-	[`ast.ValueSpec`](./ast/ValueSpec.md)
	-	[ast.FuncDecl](./ast/FuncDecl.md)
		-	Name: [ast.Ident](./ast/Ident.md)
			-	[`ast.Object`](./ast/Object.md)
				-	[`ast.Decl`](./ast/Decl.md)
					-	[`ast.Field`](./ast/Field.md)
					-	[`ast.ImportSpec`](./ast/ImportSpec.md)
					-	[`ast.TypeSpec`](./ast/TypeSpec.md)
					-	[`ast.ValueSpec`](./ast/ValueSpec.md)
					-	[`ast.FuncDecl`](./ast/FuncDecl.md)
					-	[`ast.LabeledStmt`](./ast/LabeledStmt.md)
					-	[`ast.AssignStmt`](./ast/AssignStmt.md)
					-	[`ast.Scope`](./ast/Scope.md)
-	`ast.Stmt`
	-	[ast.BadStmt](./ast/BadStmt.md)
	-	[ast.DeclStmt](./ast/DeclStmt.md)
	-	[ast.EmptyStmt](./ast/EmptyStmt.md)
	-	[ast.LabeledStmt](./ast/LabeledStmt.md)
	-	[ast.ExprStmt](./ast/ExprStmt.md)
	-	[ast.SendStmt](./ast/SendStmt.md)
	-	[ast.IncDecStmt](./ast/IncDecStmt.md)
	-	[ast.AssignStmt](./ast/AssignStmt.md)
	-	[ast.GoStmt](./ast/GoStmt.md)
	-	[ast.DeferStmt](./ast/DeferStmt.md)
	-	[ast.ReturnStmt](./ast/ReturnStmt.md)
	-	[ast.BranchStmt](./ast/BranchStmt.md)
	-	[ast.BlockStmt](./ast/BlockStmt.md)
	-	[ast.IfStmt](./ast/IfStmt.md)
	-	[ast.CaseClause](./ast/CaseClause.md)
	-	[ast.SwitchStmt](./ast/SwitchStmt.md)
	-	[ast.TypeSwitchStmt](./ast/TypeSwitchStmt.md)
	-	[ast.CommClause](./ast/CommClause.md)
	-	[ast.SelectStmt](./ast/SelectStmt.md)
	-	[ast.ForStmt](./ast/ForStmt.md)
	-	[ast.RangeStmt](./ast/RangeStmt.md)