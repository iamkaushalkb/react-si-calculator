import React, {useState} from 'react';
import AppBar from '@mui/material/AppBar';
import Toolbar from '@mui/material/Toolbar';
import Typography from '@mui/material/Typography';
import TextField from '@mui/material/TextField';
import Button from '@mui/material/Button';
import './style.css';

const App=()=>{
  const [principal, setPrincipal] = useState(0);
  const [time, setTime] = useState(0);
  const [rate, setRate] = useState(0);
  const [simple_interest, setSimpleInterest] = useState(0);
  const calcSimpleInterest=()=>{
    setSimpleInterest((principal*time*rate)/100)
  }
  return (
    <div>
      <AppBar>
        <Toolbar>
          <Typography variant="h6" component="div" sx={{ flexGrow: 1 }}>
            Simple Interest Calculator 
          </Typography>
        </Toolbar>
      </AppBar>
      <br/>
       <div className="si_body">
       <div className="si_textfield">
       <TextField onChange={(event) => setPrincipal(event.target.value)} id="standard-basic" label="Enter the Principal" variant="outlined" />
       </div>
       <div className="si_textfield">
       <TextField onChange={(event) => setTime(event.target.value)} id="standard-basic" label="Enter the Time" variant="outlined" />
       </div>       
       <div className="si_textfield">
       <TextField onChange={(event) => setRate(event.target.value)} id="standard-basic" label="Enter the Rate" variant="outlined" />
       </div>
       <div className="si_button">
       <Button onClick={()=> calcSimpleInterest()} variant="contained" size="large">Calculate</Button>
       </div>
       <div className="si_result">
       <Typography variant="h6" gutterBottom>
        Simple Interest is: {simple_interest}
       </Typography>
       </div>
       </div>
    </div>
  );
}

export default App;
