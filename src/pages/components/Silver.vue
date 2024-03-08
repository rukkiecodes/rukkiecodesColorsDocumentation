<template>
    <h3 class="mt-10">Silver</h3>
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
                <td>{{ silver50.name }}</td>
                <td>{{ silver50.hex }}</td>
                <td>
                    <v-sheet :color="silver50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ silver100.name }}</td>
                <td>{{ silver100.hex }}</td>
                <td>
                    <v-sheet :color="silver100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ silver200.name }}</td>
                <td>{{ silver200.hex }}</td>
                <td>
                    <v-sheet :color="silver200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ silver300.name }}</td>
                <td>{{ silver300.hex }}</td>
                <td>
                    <v-sheet :color="silver300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ silver400.name }}</td>
                <td>{{ silver400.hex }}</td>
                <td>
                    <v-sheet :color="silver400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ silver500.name }}</td>
                <td>{{ silver500.hex }}</td>
                <td>
                    <v-sheet :color="silver500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ silver600.name }}</td>
                <td>{{ silver600.hex }}</td>
                <td>
                    <v-sheet :color="silver600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ silver700.name }}</td>
                <td>{{ silver700.hex }}</td>
                <td>
                    <v-sheet :color="silver700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ silver800.name }}</td>
                <td>{{ silver800.hex }}</td>
                <td>
                    <v-sheet :color="silver800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ silver900.name }}</td>
                <td>{{ silver900.hex }}</td>
                <td>
                    <v-sheet :color="silver900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    silver50,
    silver100,
    silver200,
    silver300,
    silver400,
    silver500,
    silver600,
    silver700,
    silver800,
    silver900,
} from 'rukkiecodes-colors';
</script>
