<template>
    <h3 class="mt-10">Aluminum</h3>
    <v-table>
        <thead>
            <tr>
                <th class="text-left">
                    Name
                </th>
                <th class="text-left">
                    Code
                </th>
                <th class="text-left">
                    Sample
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>{{ aluminum50.name }}</td>
                <td>{{ aluminum50.hex }}</td>
                <td>
                    <v-sheet :color="aluminum50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ aluminum100.name }}</td>
                <td>{{ aluminum100.hex }}</td>
                <td>
                    <v-sheet :color="aluminum100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ aluminum200.name }}</td>
                <td>{{ aluminum200.hex }}</td>
                <td>
                    <v-sheet :color="aluminum200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ aluminum300.name }}</td>
                <td>{{ aluminum300.hex }}</td>
                <td>
                    <v-sheet :color="aluminum300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ aluminum400.name }}</td>
                <td>{{ aluminum400.hex }}</td>
                <td>
                    <v-sheet :color="aluminum400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ aluminum500.name }}</td>
                <td>{{ aluminum500.hex }}</td>
                <td>
                    <v-sheet :color="aluminum500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ aluminum600.name }}</td>
                <td>{{ aluminum600.hex }}</td>
                <td>
                    <v-sheet :color="aluminum600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ aluminum700.name }}</td>
                <td>{{ aluminum700.hex }}</td>
                <td>
                    <v-sheet :color="aluminum700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ aluminum800.name }}</td>
                <td>{{ aluminum800.hex }}</td>
                <td>
                    <v-sheet :color="aluminum800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ aluminum900.name }}</td>
                <td>{{ aluminum900.hex }}</td>
                <td>
                    <v-sheet :color="aluminum900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    aluminum50,
    aluminum100,
    aluminum200,
    aluminum300,
    aluminum400,
    aluminum500,
    aluminum600,
    aluminum700,
    aluminum800,
    aluminum900,
} from 'rukkiecodes-colors';
</script>
