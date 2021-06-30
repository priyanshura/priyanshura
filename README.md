
import React ,{Component} from 'react';
import {Link , Switch, Route} from 'react-router-dom';
import 'font-awesome/css/font-awesome.css';

class New extends Component{

    constructor(){
        super();

    }

    render(){
        
        return(
            <div className="container mt-5">
                <div className="row">
                    <div className="col-lg-12">
                        <div className="col-lg-4">
                        
                        </div>
                        <div className="col-lg-4">
                            <h6><b>Welcome</b></h6>
                            <small><i className="fa fa-plus text-danger"></i> Add task </small>
                            <br/><br/>
                            <p><b>Let's get started with a few tips</b></p>
                            <hr/>
                            <p>
                                <input type="radio"  data-toggle="collapse" data-target="#demo"/> My name is task A<br/>
                                <i className="fa fa-call"></i> 0/2
                                <hr/>
                            </p>
                            <div id="demo" className="collapse">
                                    <input type="radio"/> My name is task AA
                                    <hr/>
                                    <input type="radio"/> My name is task AB
                            </div>
                            <p>
                                <input type="radio"/> My name is task B
                                <hr/>
                                <small><i className="fa fa-plus text-danger"></i> Add task </small>
                            </p>
                            <p><b>To go further</b></p>
                            <hr/>
                            <p>
                                <a href="#">
                                    <input type="radio"/> KIckstart your projects with Template <i className="fa fa-arrow"></i>
                                </a>
                                <hr/>
                                <input type="radio"/> Click <i className="fa fa-plus"></i> next to Projects to add one of your own
                                <br/>
                                <i className="fa fa-phone-alt">0/1</i> <i className="fa fa-envelope"> 1</i>
                            </p><hr/>
                            <p>
                                <input type="radio"/> Task AAA<br/>
                                <i className="fas fa-calendar"></i> <span className="text-warning">Tomorrow</span>
                            </p><hr/>
                            <p>
                                <a href="#">
                                    <input type="radio"/> Get Organized anywhere with the Apps
                                </a>
                            </p><hr/>
                            <p>
                                <a href="#">
                                    <input type="radio"/> Learn how to use Todoist with the guide
                                </a>
                            </p><hr/>
                            <small><i className="fa fa-plus text-danger"></i> Add task</small>

                        </div>
                        <div className="col-lg-4"></div>
                    </div>
                </div>
            </div>
        )
    }
}

export default New;
