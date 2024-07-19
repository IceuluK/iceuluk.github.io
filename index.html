<!DOCTYPE html>
<html lang="en">
  
<!-- Mirrored from target-httpd.chals.io/casino/employee-login.html by HTTrack Website Copier/3.x [XR&CO'2014], Fri, 19 Jul 2024 03:33:50 GMT -->
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="shortcut icon"
      type="image/png"
      href="../../animaproject.s3.amazonaws.com/home/favicon.png"
    />
    <meta name="og:type" content="website" />
    <meta name="twitter:card" content="photo" />
    <link rel="stylesheet" type="text/css" href="css/employee-login.css" />
    <link rel="stylesheet" type="text/css" href="css/styleguide.css" />
    <link rel="stylesheet" type="text/css" href="css/globals.css" />
    <!-- <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap"
    /> -->
    <link
      rel="stylesheet"
      href="../../fonts.googleapis.com/icone91f.css?family=Material+Icons"
    />
  </head>
  <body>
    <div class="container-center-horizontal">
      <div class="employee-login screen">
        <div class="overlap-group1">
          <a href="homepage.html"
            ><img
              class="asset-102x"
              src="img/asset-10-2x%401x.png"
              alt="Asset 10@2x"
            />
          </a>
        </div>
        <div class="overlap-group">
          <div class="rectangle-3 rectangle">
            <div id="root"></div>
          </div>
        </div>
      </div>
    </div>
    <script
      crossorigin
      src="../../unpkg.com/react%4018.3.1/umd/react.production.min.js"
    ></script>
    <script
      crossorigin
      src="../../unpkg.com/react-dom%4018.3.1/umd/react-dom.production.min.js"
    ></script>
    <script src="../../unpkg.com/%40babel/standalone%407.24.10/babel.min.js"></script>
    <script
      src="../../unpkg.com/%40mui/material%405.16.4/umd/material-ui.production.min.js"
      crossorigin
    ></script>
    <script type="text/babel">
      const { useState } = React;
      const {
        TextField,
        Button,
        Container,
        Box,
        Typography,
        ThemeProvider,
        createTheme,
      } = MaterialUI;
      const darkTheme = createTheme({
        palette: {
          mode: 'dark',
          background: {
            default: '#121212',
          },
        },
      });

      const LoginForm = () => {
        const [username, setUsername] = useState('');
        const [password, setPassword] = useState('');
        const [message, setMessage] = useState('');

        const handleSubmit = (event) => {
          event.preventDefault();

          const domain = btoa(window.location.host);

          const data = {
            username,
            password,
            domain,
          };

          fetch('../../target-flask.chals.io/api/v1/authentications', {
            method: 'POST',
            headers: {
              'Content-Type': 'application/json',
              'eC1kb21haW4' : domain
            },
            body: JSON.stringify(data),
          }).then(async (response) => {
            const data = await response.json();
            if (response.status === 200) {
              setMessage('Success. Redirecting in 5.');
              console.log('Data:', data); // Handle the data
              setTimeout(() => {
                const url = window.location.href.replace("employee-login.html", `homepage.html?user=${username}`);
                console.log(url);
                window.location.href = url;
              }, 5000);
            } else {
              setMessage(data.message || 'Invalid username or password');
              console.error('Error:', data); // Handle the error data
            }
          });
        };

        return (
          <ThemeProvider theme={darkTheme}>
            <Container maxWidth="sm">
              <Box
                sx={{
                  marginTop: 8,
                  display: 'flex',
                  flexDirection: 'column',
                  alignItems: 'center',
                }}
              >
                <Typography
                  component="h1"
                  variant="h5"
                  style={{ color: '#ffffff' }}
                >
                  Employee Login
                </Typography>
                <Box sx={{ mt: 1 }}>
                  <TextField
                    margin="normal"
                    required
                    fullWidth
                    id="username"
                    label="Username"
                    name="username"
                    onChange={(e) => setUsername(e.target.value)}
                    autoComplete="username"
                    autoFocus
                  />
                  <TextField
                    margin="normal"
                    required
                    fullWidth
                    name="password"
                    label="Password"
                    type="password"
                    id="password"
                    onChange={(e) => setPassword(e.target.value)}
                    autoComplete="current-password"
                  />
                  <Button
                    type="submit"
                    fullWidth
                    variant="contained"
                    onClick={handleSubmit}
                    sx={{
                      mt: 3,
                      mb: 2,
                      backgroundColor: 'white',
                      color: 'black',
                      '&:hover': {
                        backgroundColor: '#e0e0e0',
                      },
                    }}
                  >
                    Login
                  </Button>
                  <Typography
                    variant="subtitle1"
                    style={{ mt: 20, color: '#ffffff' }}
                  >
                    {message}
                  </Typography>
                </Box>
              </Box>
            </Container>
          </ThemeProvider>
        );
      };

      ReactDOM.render(<LoginForm />, document.getElementById('root'));
    </script>
  </body>

<!-- Mirrored from target-httpd.chals.io/casino/employee-login.html by HTTrack Website Copier/3.x [XR&CO'2014], Fri, 19 Jul 2024 03:33:55 GMT -->
</html>
