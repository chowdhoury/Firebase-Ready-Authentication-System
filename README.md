#Access auth instance from any where using
```
const { * }=useContext(AuthContext)
```

#Main.jsx SetUp would be
```
<StrictMode>
    <AuthProvider>
      <RouterProvider router={router}></RouterProvider>
    </AuthProvider>
  </StrictMode>,
```
